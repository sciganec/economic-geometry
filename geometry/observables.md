# OBSERVABLES: Capital Efficiency, Risk, Monetization, and Leverage

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 5, Sections 5.1-5.2

---

## 1. Introduction to Observables

In Economic Geometry, **observables** are functions that map states ω ∈ Ω to quantitative values, revealing different aspects of a business configuration. Just as in physics, where observables like energy, momentum, and spin characterize a physical system, economic observables characterize a business configuration.

**Definition 1.1 (Observable).** An observable is a function O: Ω → ℝ (or to some other numerical space) that assigns a quantitative value to each economic state.

The principal observables in Economic Geometry are:
- **Capital Efficiency Score (CES)** — overall viability
- **Risk Profile** — exposure to various failure modes
- **Monetization Model** — revenue generation mechanism
- **Leverage** — resource multiplication capacity

---

## 2. Capital Efficiency Score (CES)

### 2.1. Definition

**Definition 2.1 (Capital Efficiency).** CES: Ω → [0,100] is defined as:

```
CES(ω) = (Fₗ(a) × M_v(v) × Pₜ(t)) - SF(ω)
```

where:
- **Fₗ: A → ℝ⁺** — founder leverage function
- **M_v: V → ℝ⁺** — market vector function
- **Pₜ: T → ℝ⁺** — phase alignment function
- **SF(ω)** — structural friction (normalized to [0,1])

The product Fₗ × M_v × Pₜ is then normalized to the [0,100] scale.

### 2.2. Component Functions

**Table 2.1. Leverage Function Fₗ(a)**

| Agent (a) | Code | Fₗ | Interpretation |
|-----------|------|-----|----------------|
| **ME** | `10` | 0.7 | Individual — limited leverage, high flexibility |
| **WE** | `11` | 1.0 | Team — optimal leverage (baseline) |
| **YOU** | `01` | 0.8 | Client-centric — leverage through demand, dependency |
| **THEY** | `00` | 0.9 | System — high leverage, inertia |

**Table 2.2. Market Vector Function M_v(v)**

| Vector (v) | Code | M_v | Interpretation |
|------------|------|-----|----------------|
| **EAST** | `10` | 1.2 | Innovation — high potential, high risk |
| **SOUTH** | `11` | 1.0 | Market — stable, baseline |
| **WEST** | `01` | 1.1 | Capital — efficient, requires accumulation |
| **NORTH** | `00` | 0.8 | Regulation — constraining, provides protection |

**Table 2.3. Phase Alignment Function Pₜ(t)**

| Phase (t) | Code | Pₜ | Interpretation |
|-----------|------|-----|----------------|
| **SPRING** | `10` | 0.9 | Creation — high risk, low predictability |
| **SUMMER** | `11` | 1.2 | Growth — optimal phase for most businesses |
| **AUTUMN** | `01` | 1.0 | Optimization — stable, predictable |
| **WINTER** | `00` | 0.6 | Decline — worst phase, requires transformation |

### 2.3. Raw CES Calculation

First compute the raw product:

```
CES_raw(ω) = Fₗ(a) × M_v(v) × Pₜ(t)
```

**Example 2.1.** ω = (WE, EAST, SUMMER) = 11 10 11
- Fₗ(WE) = 1.0
- M_v(EAST) = 1.2
- Pₜ(SUMMER) = 1.2
CES_raw = 1.0 × 1.2 × 1.2 = 1.44

**Example 2.2.** ω = (ME, NORTH, WINTER) = 10 00 00
- Fₗ(ME) = 0.7
- M_v(NORTH) = 0.8
- Pₜ(WINTER) = 0.6
CES_raw = 0.7 × 0.8 × 0.6 = 0.336

### 2.4. SF Adjustment and Normalization

The structural friction SF(ω) is subtracted, then the result is normalized to [0,100]:

```
CES(ω) = 100 × (CES_raw(ω) - SF(ω)) / CES_max
```

where CES_max is the maximum possible raw CES (achieved by optimal configuration).

For our canonical calibration:
- Maximum raw CES = 1.0 × 1.2 × 1.2 = 1.44 (achieved by WE,EAST,SUMMER or WE,SOUTH,SUMMER)
- Minimum raw CES = 0.7 × 0.8 × 0.6 = 0.336

**Example 2.3.** For ω = (WE, EAST, SUMMER) with SF = 0.1:
CES_raw = 1.44
CES = 100 × (1.44 - 0.1) / 1.44 = 100 × 1.34 / 1.44 = 93.1

**Example 2.4.** For ω = (ME, NORTH, WINTER) with SF = 0.9:
CES_raw = 0.336
CES = 100 × (0.336 - 0.9) / 1.44 = 100 × (-0.564) / 1.44 = -39.2 → clamped to 0

### 2.5. CES Interpretation Scale

| CES Range | Status | Recommendation |
|-----------|--------|----------------|
| **86–100** | Structural Advantage | GO (aggressive) |
| **71–85** | Strong Configuration | GO (with discipline) |
| **41–70** | Conditional Opportunity | PIVOT or test |
| **0–40** | Structural Misalignment | REJECT or radical transformation |

---

## 3. Risk Operator R(ω)

### 3.1. Definition

**Definition 3.1 (Risk Profile).** R: Ω → [0,1]³ (or to a risk category) maps each state to a risk vector with three components:

```
R(ω) = (R_phase, R_mismatch, R_extremes)
```

where:
- **R_phase** — base risk associated with the phase
- **R_mismatch** — risk from dimensional inconsistencies
- **R_extremes** — risk from extreme configurations

### 3.2. Component Definitions

**Table 3.1. Base Phase Risk R_phase(t)**

| Phase | Code | R_phase | Risk Character |
|-------|------|---------|----------------|
| **SPRING** | `10` | 0.8 | Uncertainty risk — product-market fit, technology viability |
| **SUMMER** | `11` | 0.3 | Scaling risk — operational capacity, competition |
| **AUTUMN** | `01` | 0.4 | Stagnation risk — innovation slowdown, market saturation |
| **WINTER** | `00` | 0.9 | Mortality risk — cash flow, relevance, transformation failure |

**Table 3.2. Mismatch Risk R_mismatch(a, v, t)**

| Mismatch Level | R_mismatch | Description |
|----------------|------------|-------------|
| Low (SF < 0.2) | 0.1 | Dimensions well-aligned |
| Moderate (0.2 ≤ SF < 0.4) | 0.3 | Some tension between dimensions |
| High (0.4 ≤ SF < 0.6) | 0.6 | Significant dimensional conflict |
| Extreme (SF ≥ 0.6) | 0.9 | Fundamental structural incompatibility |

**Table 3.3. Extreme Configuration Risk R_extremes(ω)**

| Configuration Type | R_extremes | Examples |
|-------------------|------------|----------|
| Normal | 0.0 | Most states |
| Individual in Winter | 0.3 | (ME, *, WINTER) |
| Client in Winter | 0.3 | (YOU, *, WINTER) |
| Individual in North | 0.2 | (ME, NORTH, *) |
| Client in North | 0.2 | (YOU, NORTH, *) |
| System in Spring | 0.3 | (THEY, *, SPRING) |
| Multiple extremes | Sum (capped at 1.0) | (ME, NORTH, WINTER) → 0.3+0.2+0.3 = 0.8 |

### 3.3. Composite Risk Score

For practical use, we often combine the three components into a single risk score:

```
R_total(ω) = w₁·R_phase + w₂·R_mismatch + w₃·R_extremes
```

with weights typically w₁ = w₂ = w₃ = 1/3.

**Example 3.1.** ω = (WE, EAST, SUMMER) = 11 10 11
- R_phase(SUMMER) = 0.3
- R_mismatch (SF=0.1) = 0.1
- R_extremes = 0.0
R_total = (0.3 + 0.1 + 0.0)/3 = 0.13 (low risk)

**Example 3.2.** ω = (ME, NORTH, WINTER) = 10 00 00
- R_phase(WINTER) = 0.9
- R_mismatch (SF=0.9) = 0.9
- R_extremes = 0.8 (individual + north + winter)
R_total = (0.9 + 0.9 + 0.8)/3 = 0.87 (very high risk)

### 3.4. Risk Categories

| R_total Range | Risk Level | Action |
|---------------|------------|--------|
| 0.0 - 0.2 | Very Low | Proceed normally |
| 0.2 - 0.4 | Low | Monitor standard risks |
| 0.4 - 0.6 | Moderate | Develop mitigation strategies |
| 0.6 - 0.8 | High | Immediate attention required |
| 0.8 - 1.0 | Critical | Consider pivot or exit |

---

## 4. Monetization Operator M(a, v)

### 4.1. Definition

**Definition 4.1 (Monetization Model).** M: A × V → M, where M is the set of monetization mechanisms, maps each combination of agency and vector to a canonical revenue model.

### 4.2. Complete Monetization Table

| a\v | EAST (10) | SOUTH (11) | WEST (01) | NORTH (00) |
|-----|-----------|------------|-----------|------------|
| **ME (10)** | Patent licensing, R&D consulting | Direct sales, commissions | Investments, royalties, dividends | Government contracts, grants |
| **WE (11)** | R&D outsourcing, technology licensing | Distribution partnerships, retail | Venture capital, private equity funds | Standards development, certification |
| **YOU (01)** | Custom development, solution selling | Subscriptions, transaction fees | Crowdfunding, pre-orders | Compliance services, regulatory reporting |
| **THEY (00)** | Platform API fees, developer ecosystem | Marketplace commissions, listing fees | Investment platform fees, asset management | Regulator-as-service, compliance-as-platform |

### 4.3. Detailed Model Descriptions

**EAST (Innovation) Monetization:**

| Agency | Model | Description | Example |
|--------|-------|-------------|---------|
| **ME** | Patent licensing | License IP to manufacturers | Individual inventor |
| **ME** | R&D consulting | Paid expertise for innovation projects | Tech consultant |
| **WE** | R&D outsourcing | Contract research for other companies | Research lab |
| **WE** | Technology licensing | License software/platform to enterprises | Software company |
| **YOU** | Custom development | Build specific solutions for clients | Dev shop |
| **YOU** | Solution selling | Sell complete solutions, not just products | Enterprise sales |
| **THEY** | Platform API fees | Charge for access to platform capabilities | Twilio, Stripe |
| **THEY** | Developer ecosystem | Revenue sharing with app developers | iOS App Store |

**SOUTH (Market) Monetization:**

| Agency | Model | Description | Example |
|--------|-------|-------------|---------|
| **ME** | Direct sales | Sell directly to customers | Independent sales rep |
| **ME** | Commissions | Percentage of sales facilitated | Broker |
| **WE** | Distribution partnerships | Partner with distributors | Wholesaler |
| **WE** | Retail | Direct to consumer stores | Retail chain |
| **YOU** | Subscriptions | Recurring payments for access | Netflix, Spotify |
| **YOU** | Transaction fees | Per-transaction charges | Payment processor |
| **THEY** | Marketplace commissions | Take rate on transactions | Amazon, eBay |
| **THEY** | Listing fees | Charge to list products | Etsy, Airbnb |

**WEST (Capital) Monetization:**

| Agency | Model | Description | Example |
|--------|-------|-------------|---------|
| **ME** | Investments | Return on invested capital | Angel investor |
| **ME** | Royalties | Percentage of revenue/licensing | Inventor |
| **ME** | Dividends | Share of profits | Shareholder |
| **WE** | Venture capital | Returns from startup investments | VC firm |
| **WE** | Private equity | Returns from mature company investments | PE firm |
| **YOU** | Crowdfunding | Pre-purchase or donation-based funding | Kickstarter backer |
| **YOU** | Pre-orders | Pay before product exists | Game pre-orders |
| **THEY** | Investment platform fees | Fees for facilitating investments | Robinhood, Coinbase |
| **THEY** | Asset management fees | Percentage of assets under management | BlackRock, Vanguard |

**NORTH (Authority) Monetization:**

| Agency | Model | Description | Example |
|--------|-------|-------------|---------|
| **ME** | Government contracts | Paid for specific services | Government consultant |
| **ME** | Grants | Funding for research/projects | Academic researcher |
| **WE** | Standards development | Funding from standard adoption | IEEE, ISO |
| **WE** | Certification | Fees for certifying compliance | Underwriters Laboratories |
| **YOU** | Compliance services | Help clients meet regulations | Compliance consultant |
| **YOU** | Regulatory reporting | File reports on behalf of clients | Accounting firm |
| **THEY** | Regulator-as-service | Government agency providing services | Patent office |
| **THEY** | Compliance-as-platform | Platform for managing compliance | Compliance software |

### 4.4. Monetization Matrix Properties

**Theorem 4.1 (Monetization Determinacy).** The monetization model is uniquely determined by the pair (a, v). Phase t influences the execution but not the fundamental mechanism.

**Theorem 4.2 (Diagonal Similarity).** States on the diagonal (where a and v have the same code) share similar monetization patterns:
- (ME, EAST) — individual innovation
- (WE, SOUTH) — team market
- (YOU, WEST) — client capital
- (THEY, NORTH) — system authority

---

## 5. Leverage Operator L(ω)

### 5.1. Definition

**Definition 5.1 (Leverage).** L: Ω → ℝ⁺ measures the capacity of a business configuration to control resources beyond its direct ownership:

```
L(ω) = Fₗ(a) × L_v(v) × L_t(t)
```

where:
- **Fₗ(a)** — base leverage from agency (as defined in CES)
- **L_v(v)** — vector leverage multiplier
- **L_t(t)** — phase leverage multiplier

### 5.2. Leverage Multipliers

**Table 5.1. Vector Leverage Multiplier L_v(v)**

| Vector | Code | L_v | Rationale |
|--------|------|-----|-----------|
| **EAST** | `10` | 1.3 | Technology creates leverage through scalability |
| **SOUTH** | `11` | 1.0 | Market provides baseline leverage |
| **WEST** | `01` | 1.2 | Capital creates leverage through investment |
| **NORTH** | `00` | 0.9 | Regulation constrains leverage |

**Table 5.2. Phase Leverage Multiplier L_t(t)**

| Phase | Code | L_t | Rationale |
|-------|------|-----|-----------|
| **SPRING** | `10` | 0.8 | Creation phase — low leverage, high uncertainty |
| **SUMMER** | `11` | 1.2 | Growth phase — maximum leverage |
| **AUTUMN** | `01` | 1.1 | Optimization phase — maintained leverage |
| **WINTER** | `00` | 0.7 | Decline phase — leverage collapses |

### 5.3. Example Calculations

**Example 5.1.** ω = (THEY, EAST, SUMMER) = 00 10 11
- Fₗ(THEY) = 0.9
- L_v(EAST) = 1.3
- L_t(SUMMER) = 1.2
L = 0.9 × 1.3 × 1.2 = 1.404 (high leverage)

**Example 5.2.** ω = (ME, NORTH, WINTER) = 10 00 00
- Fₗ(ME) = 0.7
- L_v(NORTH) = 0.9
- L_t(WINTER) = 0.7
L = 0.7 × 0.9 × 0.7 = 0.441 (low leverage)

**Example 5.3.** ω = (WE, SOUTH, SUMMER) = 11 11 11
- Fₗ(WE) = 1.0
- L_v(SOUTH) = 1.0
- L_t(SUMMER) = 1.2
L = 1.0 × 1.0 × 1.2 = 1.2 (good leverage)

### 5.4. Leverage Interpretation

| L Range | Leverage Level | Implication |
|---------|----------------|-------------|
| > 1.3 | Extreme leverage | High growth potential, high risk |
| 1.1 - 1.3 | High leverage | Strong resource multiplication |
| 0.9 - 1.1 | Moderate leverage | Balanced |
| 0.7 - 0.9 | Low leverage | Resource-constrained |
| < 0.7 | Very low leverage | Difficulty scaling |

---

## 6. Relationships Between Observables

### 6.1. CES and Risk

Generally, high CES correlates with low risk, but not perfectly:
- Some high-CES states (e.g., EAST in SPRING) have significant risk
- Some moderate-CES states may have low risk (e.g., NORTH in AUTUMN)

### 6.2. Leverage and CES

Leverage contributes positively to CES through Fₗ, but high leverage also increases risk exposure:
- L > 1.3 often indicates high-risk, high-reward configurations
- L < 0.7 usually corresponds to CES < 40

### 6.3. Monetization and Leverage

Different monetization models have characteristic leverage profiles:
- Platform models (THEY×EAST) tend to have highest leverage
- Service models (ME×SOUTH) tend to have lower leverage

---

## 7. Summary Table of Observables

| Observable | Symbol | Range | Primary Dependence | Business Meaning |
|------------|--------|-------|-------------------|------------------|
| **Capital Efficiency** | CES | [0,100] | Fₗ×M_v×Pₜ - SF | Overall viability |
| **Risk** | R | [0,1]³ or [0,1] | Phase, mismatch, extremes | Exposure to failure |
| **Monetization** | M | Categorical | (a, v) pair | Revenue mechanism |
| **Leverage** | L | [0,∞) | Fₗ×L_v×L_t | Resource multiplication |

**Key Insight:** These four observables provide a complete quantitative characterization of any business configuration in Ω, enabling systematic comparison, evaluation, and strategic decision-making.

---

*This document establishes the observable quantities in Economic Geometry, providing the foundation for quantitative business analysis and comparison.*
