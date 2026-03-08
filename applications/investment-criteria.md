# INVESTMENT CRITERIA: Geometric Due Diligence

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 12, Section 12.1

---

## 1. Introduction to Geometric Due Diligence

Traditional investment analysis focuses on financial metrics, market size, and team quality. Economic Geometry adds a new dimension: **structural analysis** of the business configuration itself. This document provides a framework for evaluating investment opportunities based on their position in Ω, their trajectory, and their potential for structural improvement.

**Core Principle:** The best investments are those in strong structural configurations with clear paths to even better configurations.

---

## 2. The Investment Decision Framework

### 2.1. Three-Level Analysis

```
Level 1: Current State Assessment
        ↓
Level 2: Trajectory Analysis
        ↓
Level 3: Structural Potential
        ↓
Investment Decision
```

### 2.2. The Investment Scorecard

| Category | Metric | Weight | Score |
|----------|--------|--------|-------|
| **Current State** | CES | 25% | /100 |
| **Current State** | SF | 20% | /100 |
| **Trajectory** | CES trend | 15% | /100 |
| **Trajectory** | SF trend | 15% | /100 |
| **Potential** | Adjacent states CES | 15% | /100 |
| **Potential** | Transformation ease | 10% | /100 |
| **Total** | | 100% | /100 |

---

## 3. Level 1: Current State Assessment

### 3.1. CES Evaluation

| CES Range | Grade | Interpretation | Action |
|-----------|-------|----------------|--------|
| 86-100 | A+ | Structural advantage | Aggressive buy |
| 71-85 | A | Strong configuration | Buy |
| 56-70 | B+ | Good potential | Consider |
| 41-55 | B | Conditional | Hold/analyze |
| 26-40 | C | Struggling | Pass unless turnaround |
| 0-25 | D | Critical | Avoid |

**Investment Rule:** Minimum CES for investment: **55** (B grade) for growth investments, **45** for value/distressed.

### 3.2. SF Evaluation

| SF Range | Grade | Interpretation | Action |
|----------|-------|----------------|--------|
| 0.0-0.2 | A | Very low friction | Excellent |
| 0.2-0.3 | B+ | Low friction | Good |
| 0.3-0.4 | B | Moderate-low | Acceptable |
| 0.4-0.5 | C+ | Moderate | Caution |
| 0.5-0.6 | C | Moderate-high | High risk |
| 0.6-0.7 | D | High | Very high risk |
| 0.7-1.0 | F | Critical | Avoid |

**Investment Rule:** Maximum SF for investment: **0.4** (C+ grade) for most investments, **0.5** for distressed specialists.

### 3.3. State Quality Matrix

Combine CES and SF into a state quality score:

```
CES/SF | 0.0-0.2 | 0.2-0.3 | 0.3-0.4 | 0.4-0.5 | 0.5+
-------|---------|---------|---------|---------|------
86-100 | Elite   | Prime   | Good    | Fair    | Poor
71-85  | Prime   | Good    | Fair    | Poor    | Bad
56-70  | Good    | Fair    | Poor    | Bad     | Terrible
41-55  | Fair    | Poor    | Bad     | Terrible| Avoid
0-40   | Poor    | Bad     | Terrible| Avoid   | Avoid
```

**Investment Zones:**
- **Green (Elite/Prime/Good):** Strong buy candidates
- **Yellow (Fair/Poor):** Further analysis required
- **Red (Bad/Terrible/Avoid):** Reject

---

## 4. Level 2: Trajectory Analysis

### 4.1. CES Trend

| Trend (12 months) | Score | Interpretation |
|-------------------|-------|----------------|
| +10+ points | 100 | Accelerating |
| +5 to +10 | 80 | Growing |
| 0 to +5 | 60 | Stable |
| -5 to 0 | 40 | Declining |
| -10 to -5 | 20 | Deteriorating |
| <-10 | 0 | Crashing |

### 4.2. SF Trend

| Trend (12 months) | Score | Interpretation |
|-------------------|-------|----------------|
| -0.2+ | 100 | Rapidly cohering |
| -0.1 to -0.2 | 80 | Improving |
| -0.05 to -0.1 | 60 | Slightly improving |
| -0.05 to +0.05 | 40 | Stable |
| +0.05 to +0.1 | 20 | Deteriorating |
| +0.1+ | 0 | Fragmenting |

### 4.3. Phase Trajectory

| Phase Transition | Score | Interpretation |
|------------------|-------|----------------|
| SPRING → SUMMER | 100 | Entering growth |
| SUMMER → SUMMER | 80 | Sustained growth |
| SUMMER → AUTUMN | 60 | Maturing |
| AUTUMN → AUTUMN | 40 | Stable maturity |
| AUTUMN → WINTER | 20 | Entering decline |
| WINTER → anything | 0-100 | Depends on direction |

### 4.4. Vector Stability

| Vector Change | Score | Interpretation |
|---------------|-------|----------------|
| Stable in optimal vector | 100 | Focused |
| Expanding to new vector | 80 | Diversifying |
| Shifting vector | 60 | Pivoting |
| Unstable vector | 40 | Confused |
| Wrong vector for phase | 20 | Mismatched |

---

## 5. Level 3: Structural Potential

### 5.1. Adjacent State Analysis

For current state ω, examine all neighboring states (d=1) and their CES:

| Neighbor | CES | Gain/Loss | Operator |
|----------|-----|-----------|----------|
| ω₁ | 82 | +10 | T_SUMMER |
| ω₂ | 75 | +3 | T_SOUTH |
| ω₃ | 68 | -4 | T_AUTUMN |
| ω₄ | 65 | -7 | T_WEST |

**Potential Score:** Weighted average of best possible gains.

### 5.2. Transformation Ease

| Factor | Weight | Scoring |
|--------|--------|---------|
| Capital required | 30% | Low=100, Medium=60, High=20 |
| Time required | 30% | <6mo=100, 6-18mo=60, >18mo=20 |
| Execution risk | 40% | Low=100, Medium=60, High=20 |

**Transformation Ease Score** = weighted average of above.

### 5.3. Destination State Quality

Evaluate the best possible future state ω* reachable within 2-3 transitions:

| Metric | Value |
|--------|-------|
| ω* CES | 85 |
| ω* SF | 0.15 |
| Distance from current | 2 |
| Transitions required | 2 |

**Destination Score** = (CES(ω*) × (1 - SF(ω*))) / max possible

---

## 6. Investment Thresholds by Strategy

### 6.1. Venture Capital / Early Stage

| Metric | Minimum | Target |
|--------|---------|--------|
| CES | 40 | 50+ |
| SF | <0.5 | <0.4 |
| CES trend | + | ++ |
| Phase | SPRING or early SUMMER | SUMMER |
| Adjacent gain | +15+ | +20+ |

**Typical targets:** (WE, EAST, SPRING), (WE, EAST, SUMMER), (ME, EAST, SPRING)

### 6.2. Growth Equity

| Metric | Minimum | Target |
|--------|---------|--------|
| CES | 60 | 70+ |
| SF | <0.4 | <0.3 |
| CES trend | +5+ | +10+ |
| Phase | SUMMER | SUMMER |
| Adjacent gain | +10+ | +15+ |

**Typical targets:** (WE, EAST, SUMMER), (WE, SOUTH, SUMMER), (THEY, EAST, SUMMER)

### 6.3. Buyout / Late Stage

| Metric | Minimum | Target |
|--------|---------|--------|
| CES | 55 | 65+ |
| SF | <0.4 | <0.3 |
| CES trend | Stable | Stable or slightly up |
| Phase | AUTUMN | AUTUMN |
| Adjacent gain | +5+ | +10+ |

**Typical targets:** (WE, EAST, AUTUMN), (WE, SOUTH, AUTUMN), (THEY, EAST, AUTUMN)

### 6.4. Distressed / Turnaround

| Metric | Minimum | Target |
|--------|---------|--------|
| CES | 20 | 30+ |
| SF | <0.7 | <0.6 |
| CES trend | Bottoming | Improving |
| Phase | WINTER | WINTER with exit path |
| Transformation ease | Medium+ | High |

**Typical targets:** (WE, EAST, WINTER), (THEY, SOUTH, WINTER) with clear path to SPRING

---

## 7. The Investment Decision Matrix

### 7.1. Combine Scores

| Score Range | Rating | Action |
|-------------|--------|--------|
| 90-100 | A+ | Aggressive buy |
| 80-89 | A | Buy |
| 70-79 | B+ | Consider |
| 60-69 | B | Hold/analyze more |
| 50-59 | C | Pass |
| <50 | D | Reject |

### 7.2. Strategy-Specific Adjustments

| Strategy | Add to Score | Subtract from Score |
|----------|--------------|---------------------|
| VC/early | +5 if SPRING phase | -10 if SF > 0.5 |
| Growth | +10 if SUMMER phase | -10 if CES < 60 |
| Buyout | +10 if AUTUMN phase | -10 if CES trend down |
| Distressed | +20 if clear exit path | -20 if SF > 0.7 |

---

## 8. Red Flags and Deal Killers

### 8.1. Absolute Rejection Criteria

| Condition | Reason |
|-----------|--------|
| SF > 0.7 | Structural friction too high |
| CES < 20 | Business fundamentally broken |
| CES dropping >20 points/year | Accelerating decline |
| WINTER phase with no exit path | Likely terminal |
| Phase denial (AUTUMN claiming SUMMER) | Management delusion |

### 8.2. Serious Concerns

| Condition | Action |
|-----------|--------|
| SF 0.5-0.7 | Require significant discount |
| CES 20-40 | Require clear turnaround plan |
| Vector mismatch | Verify management awareness |
| Agency crisis | Deep dive on governance |
| Negative CES trend | Demand explanation and proof of reversal |

### 8.3. Due Diligence Questions by Finding

| Finding | Question to Ask |
|---------|-----------------|
| High SF | What's causing internal tension? |
| Low CES | Why is efficiency low? |
| Wrong vector | Why this direction? |
| Phase mismatch | Why do you believe you're in different phase? |
| Poor trend | What's changing? |

---

## 9. Sector-Specific Criteria

### 9.1. Technology (EAST vector)

| Phase | CES Target | SF Target | Notes |
|-------|------------|-----------|-------|
| SPRING | 40-50 | <0.4 | Product risk, team focus |
| SUMMER | 70-85 | <0.2 | Growth at scale |
| AUTUMN | 60-75 | <0.3 | Margin focus |

### 9.2. Retail/Market (SOUTH vector)

| Phase | CES Target | SF Target | Notes |
|-------|------------|-----------|-------|
| SPRING | 35-45 | <0.4 | Market validation key |
| SUMMER | 70-82 | <0.2 | Unit economics critical |
| AUTUMN | 60-72 | <0.3 | Same-store sales, retention |

### 9.3. Finance (WEST vector)

| Phase | CES Target | SF Target | Notes |
|-------|------------|-----------|-------|
| SPRING | 35-45 | <0.4 | Regulatory approvals |
| SUMMER | 65-75 | <0.25 | AUM growth |
| AUTUMN | 60-70 | <0.3 | Margin, returns |

### 9.4. Healthcare/Regulatory (NORTH vector)

| Phase | CES Target | SF Target | Notes |
|-------|------------|-----------|-------|
| SPRING | 30-40 | <0.5 | Clinical/regulatory risk |
| SUMMER | 55-65 | <0.3 | Approval, adoption |
| AUTUMN | 50-60 | <0.35 | Pricing, reimbursement |

---

## 10. Case Studies

### 10.1. Example A: Growth-Stage SaaS

**Company:** Series B SaaS company, 100% YoY growth, 80% gross margins, raising at $500M valuation.

**State Identification:**
- Agency: WE (founding team still leading)
- Vector: EAST (technology-driven)
- Phase: SUMMER (hypergrowth)

**Scorecard:**

| Metric | Value | Score |
|--------|-------|-------|
| CES | 82 | 95 |
| SF | 0.15 | 95 |
| CES trend | +10 | 80 |
| SF trend | -0.05 | 70 |
| Adjacent states | (WE,SOUTH,SUM): 82 (0 gain) | 50 |
| Transformation ease | Easy to add market focus | 80 |
| **Total** | | **82 (A-)** |

**Decision:** Strong buy for growth equity.

### 10.2. Example B: Mature Retail Chain

**Company:** National retailer, 2% growth, 5% margins, trading at 8x earnings.

**State Identification:**
- Agency: THEY (institutional)
- Vector: SOUTH (market-facing)
- Phase: AUTUMN (mature)

**Scorecard:**

| Metric | Value | Score |
|--------|-------|-------|
| CES | 68 | 75 |
| SF | 0.30 | 70 |
| CES trend | -2 | 50 |
| SF trend | +0.05 | 40 |
| Adjacent states | (THEY,SOUTH,SUM): 82 (+14) | 90 |
| Transformation ease | Difficult (large company) | 40 |
| **Total** | | **62 (B-)** |

**Decision:** Consider for value, requires transformation plan.

### 10.3. Example C: Early-Stage Biotech

**Company:** Pre-revenue biotech, promising Phase 2 data, raising Series C.

**State Identification:**
- Agency: WE (scientific founders + management)
- Vector: EAST (R&D focus)
- Phase: SPRING (pre-commercial)

**Scorecard:**

| Metric | Value | Score |
|--------|-------|-------|
| CES | 45 | 50 |
| SF | 0.35 | 60 |
| CES trend | +15 (expectation) | 90 |
| SF trend | -0.10 | 80 |
| Adjacent states | (WE,EAST,SUM): 75 (+30) | 100 |
| Transformation ease | Binary (approval risk) | 30 |
| **Total** | | **68 (B)** |

**Decision:** High-risk/high-reward, suitable for specialized healthcare investors.

---

## 11. Portfolio Integration

### 11.1. Position Sizing by Score

| Score | Position Size |
|-------|---------------|
| 90-100 | 2-3x normal |
| 80-89 | 1.5x normal |
| 70-79 | 1.0x normal |
| 60-69 | 0.5x normal |
| <60 | 0 or watchlist |

### 11.2. Portfolio Construction Integration

After scoring individual investments, evaluate portfolio-level metrics:

| Metric | Target |
|--------|--------|
| Average CES | >65 |
| Average SF | <0.3 |
| Min distance | >3 (for n<10) |
| Phase coverage | ≥2 phases |
| Agency coverage | ≥3 agencies |
| Vector coverage | ≥3 vectors |

### 11.3. Ongoing Monitoring

| Frequency | Action |
|-----------|--------|
| Quarterly | Recalculate CES and SF |
| Semi-annual | Assess trajectory |
| Annual | Full re-score |
| Event-driven | Re-score after major changes |

---

## 12. Summary: The Geometric Investor's Checklist

### 12.1. Pre-Investment

- [ ] Identify current state ω
- [ ] Calculate CES and SF
- [ ] Assess 12-month trends
- [ ] Identify adjacent states and potential gains
- [ ] Evaluate transformation ease
- [ ] Compare to strategy-specific thresholds
- [ ] Check for red flags
- [ ] Calculate investment score

### 12.2. Due Diligence Questions

- [ ] Does management understand their structural configuration?
- [ ] Is their strategy aligned with their current phase?
- [ ] Do they have a credible path to better states?
- [ ] Are they aware of adjacent opportunities?
- [ ] Is the vector appropriate for the phase?
- [ ] Is the agency appropriate for the scale?

### 12.3. Post-Investment Monitoring

- [ ] Track CES and SF quarterly
- [ ] Watch for phase transitions
- [ ] Monitor vector stability
- [ ] Watch for agency changes
- [ ] Re-score annually

---

## 13. Quick Reference Card

| Metric | Target | Avoid |
|--------|--------|-------|
| **CES** | >55 (growth), >45 (value) | <40 |
| **SF** | <0.4 | >0.6 |
| **CES trend** | Positive | Negative >10 pts |
| **SF trend** | Decreasing | Increasing |
| **Phase** | SUMMER (growth), AUTUMN (value) | WINTER (unless distressed) |
| **Vector** | Aligned with phase | Mismatched |
| **Agency** | Appropriate for scale | Wrong for phase |

**The Golden Rule:** Invest in companies with CES > 55, SF < 0.4, and a clear path to even better configurations.

---

*This document provides a comprehensive framework for investment decision-making based on Economic Geometry, enabling investors to evaluate opportunities based on structural configuration rather than traditional metrics alone.*
