# STARTUP FAILURES: Structural Analysis of Crashes

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 9, Section 9.3

---

## 1. Introduction to Failure Analysis

In Economic Geometry, business failures are not random events but follow predictable structural patterns. By analyzing failed ventures through the lens of Ω, we can identify common failure modes, critical mistakes, and warning signs that precede collapse.

**Definition of Failure:** A business is considered to have failed when it:
- Enters (THEY, *, WINTER) and cannot recover
- Remains in WINTER phase for extended period
- Exits the space entirely (bankruptcy, liquidation)

---

## 2. Common Failure Patterns

### 2.1. The Five Archetypal Failure Modes

| Failure Mode | Path | Example | Frequency |
|--------------|------|---------|-----------|
| **Premature Scaling** | SPRING → SUMMER → WINTER (skip AUTUMN) | Webvan, Pets.com | 35% |
| **Failure to Pivot** | Stuck in AUTUMN → WINTER | Kodak, Blockbuster | 25% |
| **Vector Mismatch** | Wrong vector for agency/phase | Quibi, Juicero | 20% |
| **Agency Crisis** | WE → ME or YOU at wrong time | Founder ouster disasters | 10% |
| **Phase Denial** | Refusing to acknowledge WINTER | Enron, Theranos | 10% |

### 2.2. The Failure Trajectory Map

```
Normal Path:    SPRING → SUMMER → AUTUMN → [optional] WINTER
                    ↓        ↓        ↓
Failure Paths:  SPRING → WINTER (never reach SUMMER)
                    ↓        ↓
                SUMMER → WINTER (skip AUTUMN)
                    ↓        ↓
                AUTUMN → WINTER (fail to transform)
                    ↓        ↓
                Any phase → WINTER (catastrophic event)
```

---

## 3. Case Study 1: Webvan — Premature Scaling

### 3.1. Company Background

**Webvan** (1996-2001) was an online grocery delivery service that raised over $800 million, built massive infrastructure, and collapsed in less than two years of operation.

| Metric | Value |
|--------|-------|
| Founded | 1996 |
| IPO | 1999 ($8.5B peak market cap) |
| Bankruptcy | 2001 |
| Money raised | $800M+ |
| Employees at peak | 2,000+ |

### 3.2. Trajectory Analysis

| Year | State | Code | CES | SF | Phase |
|------|-------|------|-----|-----|-------|
| 1996 | (WE, EAST, SPRING) | 11 10 11 | 48 | 0.35 | Early startup |
| 1998 | (WE, EAST, SUMMER) | 11 10 10 | 65 | 0.25 | Tech scaling |
| 1999 | (WE, SOUTH, SUMMER) | 11 11 10 | 70 | 0.20 | Market expansion |
| 2000 | (WE, SOUTH, WINTER) | 11 11 00 | 22 | 0.70 | Collapse |

### 3.3. Critical Mistake Analysis

**Mistake 1: Skipping AUTUMN entirely**

```
Normal:     SPRING → SUMMER → AUTUMN → (optional) WINTER
Webvan:     SPRING → SUMMER → WINTER
```

Webvan went directly from SUMMER to WINTER without ever experiencing AUTUMN's optimization and efficiency focus.

**Mistake 2: Premature T_SOUTH**

At (WE, EAST, SUMMER) with CES=65, SF=0.25, Webvan applied T_SOUTH before achieving operational excellence:

| Before T_SOUTH | After T_SOUTH |
|----------------|---------------|
| (WE, EAST, SUMMER) | (WE, SOUTH, SUMMER) |
| Technology focus | Market expansion |
| SF=0.25 | SF=0.20 (actually improved temporarily) |
| CES=65 | CES=70 |

**The problem:** The underlying unit economics weren't viable. Technology (EAST) wasn't mature enough to support market expansion (SOUTH).

**Mistake 3: Massive infrastructure investment before validation**

Webvan built:
- $1 billion automated warehouses
- Fleet of delivery trucks
- Nationwide expansion plans

All based on untested assumptions about demand.

### 3.4. Warning Signs Ignored

| Indicator | Value | Warning |
|-----------|-------|---------|
| Burn rate | $100M+/year | Unsustainable |
| Customer acquisition cost | > LTV | Negative unit economics |
| SF trend | 0.25 → 0.20 (improving, but masking problems) | False positive |
| CES trend | 48 → 65 → 70 → 22 | Steep drop at end |

### 3.5. Failure Mode Classification

**Primary Failure Mode:** Premature Scaling (SPRING/SUMMER → WINTER)
**Secondary Factor:** Vector Mismatch (SOUTH before EAST was ready)

---

## 4. Case Study 2: Kodak — Failure to Pivot

### 4.1. Company Background

**Kodak** (1888-2012) dominated photography for a century, invented the digital camera in 1975, but failed to transition and filed for bankruptcy in 2012.

| Metric | Value |
|--------|-------|
| Founded | 1888 |
| Peak | 1976 (90% film market, 85% camera market) |
| Bankruptcy | 2012 |
| Peak employees | 145,000 (1988) |
| Digital camera invented | 1975 |

### 4.2. Trajectory Analysis

| Year | State | Code | CES | SF | Phase |
|------|-------|------|-----|-----|-------|
| 1975 | (THEY, EAST, SPRING) | 00 10 11 | 48 | 0.40 | Digital camera invented |
| 1980 | (THEY, EAST, SUMMER) | 00 10 10 | 75 | 0.20 | Technology leadership |
| 1990 | (THEY, NORTH, AUTUMN) | 00 00 01 | 58 | 0.35 | Regulatory focus |
| 2000 | (THEY, NORTH, WINTER) | 00 00 00 | 22 | 0.70 | Decline |
| 2012 | Bankruptcy | — | 0 | 1.0 | End |

### 4.3. Critical Mistake Analysis

**Mistake 1: T_NORTH instead of T_SOUTH**

The critical decision point was in the 1980s:

```
Option A (Chosen): (THEY, EAST, SUMMER) → T_NORTH → (THEY, NORTH, AUTUMN)
Option B (Not chosen): (THEY, EAST, SUMMER) → T_SOUTH → (THEY, SOUTH, SUMMER)
```

**Why T_NORTH was chosen:**
- Film business was highly profitable
- Patent portfolio was valuable
- Regulatory barriers protected film
- Digital would cannibalize film

**Why T_SOUTH would have been better:**
- Market adoption of digital was inevitable
- Early mover advantage in digital photography
- Brand could have transferred to digital

**Mistake 2: Phase denial**

Kodak remained in AUTUMN denial while actually entering WINTER:

| Year | Actual Phase | Kodak's Belief | Consequence |
|------|--------------|----------------|-------------|
| 1990 | Early AUTUMN | Still SUMMER | Missed digital transition |
| 1995 | AUTUMN | "Film has decades left" | Delayed investment |
| 2000 | WINTER entry | "We can still recover" | No radical action |
| 2005 | WINTER | Restructuring will work | Too little, too late |

**Mistake 3: Agency ossification**

Kodak was firmly in THEY agency — institutional, bureaucratic, risk-averse. It lacked the flexibility to pivot:

| THEY Characteristics | Kodak Reality |
|----------------------|---------------|
| Risk-averse | Yes — protected film at all costs |
| Slow decision-making | Yes — years to respond to digital |
| Captured by existing business | Yes — film was 90%+ of revenue |
| Innovation stifled | Yes — digital kept in R&D |

### 4.4. Warning Signs Ignored

| Indicator | 1980s | 1990s | 2000s |
|-----------|-------|-------|-------|
| Film volume | Peak | Declining | Crashing |
| Digital adoption | Niche | Growing | Mainstream |
| SF | 0.20 | 0.35 | 0.70 |
| CES | 75 | 58 | 22 |

### 4.5. Failure Mode Classification

**Primary Failure Mode:** Failure to Pivot (AUTUMN → WINTER)
**Secondary Factor:** Phase Denial (refusing to acknowledge reality)

---

## 5. Case Study 3: Pets.com — Dot-Com Bubble Failure

### 5.1. Company Background

**Pets.com** (1998-2000) was an online pet supply retailer that became iconic for its sock puppet mascot and spectacular collapse.

| Metric | Value |
|--------|-------|
| Founded | 1998 |
| IPO | February 2000 |
| Bankruptcy | November 2000 |
| Money raised | $300M |
| Sock puppet | $2M Super Bowl ad |

### 5.2. Trajectory Analysis

| Year | State | Code | CES | SF | Phase |
|------|-------|------|-----|-----|-------|
| 1998 | (WE, EAST, SPRING) | 11 10 11 | 45 | 0.35 | Early startup |
| 1999 | (WE, EAST, SUMMER) | 11 10 10 | 62 | 0.25 | Tech scaling |
| 2000 | (WE, SOUTH, SUMMER) | 11 11 10 | 68 | 0.20 | Market expansion |
| 2000 | (WE, SOUTH, WINTER) | 11 11 00 | 15 | 0.80 | Collapse |

### 5.3. Critical Mistake Analysis

**Mistake 1: Negative unit economics**

| Metric | Value |
|--------|-------|
| Average sale | $36 |
| Shipping cost | $8 |
| Product cost | $20 |
| Marketing cost | $15 |
| **Loss per sale** | **-$7** |

**Structural interpretation:** The business model was fundamentally flawed. No amount of scaling (SOUTH) could fix negative unit economics.

**Mistake 2: T_SOUTH before fixing EAST**

Pets.com applied T_SOUTH while still having fundamental EAST (technology/operations) problems:

| Required | Actual |
|----------|--------|
| Efficient fulfillment | Inefficient, high-cost |
| Economies of scale | Impossible with negative margin |
| Customer retention | Low (one-time buyers) |

**Mistake 3: Marketing before product**

The famous sock puppet was a brilliant marketing campaign for a business that didn't work:

- $2M Super Bowl ad
- Massive brand awareness
- But each new customer cost more than they'd ever generate

### 5.4. Warning Signs Ignored

| Indicator | Value | Warning |
|-----------|-------|---------|
| Unit economics | Negative | Business model broken |
| Burn rate | Millions/month | Runway measured in months |
| SF trend | 0.35 → 0.25 → 0.20 → 0.80 | Sudden spike at end |
| CES trend | 45 → 62 → 68 → 15 | Peak before crash |

### 5.5. Failure Mode Classification

**Primary Failure Mode:** Premature Scaling (SUMMER → WINTER)
**Secondary Factor:** Vector Mismatch (SOUTH without viable EAST)

---

## 6. Case Study 4: Theranos — Fraud and Deception

### 6.1. Company Background

**Theranos** (2003-2018) claimed to revolutionize blood testing with a device that could run hundreds of tests from a finger prick. The technology never worked.

| Metric | Value |
|--------|-------|
| Founded | 2003 |
| Peak valuation | $9B (2015) |
| Investors | $700M+ |
| Fraud exposed | 2015 (WSJ) |
| Dissolved | 2018 |

### 6.2. Trajectory Analysis

| Year | State | Code | CES | SF | Phase |
|------|-------|------|-----|-----|-------|
| 2003 | (ME, EAST, SPRING) | 10 10 11 | 42 | 0.30 | Elizabeth Holmes founder |
| 2005 | (WE, EAST, SPRING) | 11 10 11 | 52 | 0.30 | Team building |
| 2010 | (WE, EAST, SUMMER) | 11 10 10 | 75 | 0.20 | Growth phase |
| 2013 | (WE, EAST, SUMMER) | 11 10 10 | 82 | 0.15 | Peak hype |
| 2015 | (WE, EAST, WINTER) | 11 10 00 | 25 | 0.75 | Fraud exposed |
| 2018 | (THEY, NORTH, WINTER) | 00 00 00 | 5 | 0.95 | Legal dissolution |

### 6.3. Critical Mistake Analysis

**Mistake 1: Fraud (not a structural issue but a moral one)**

Theranos's fundamental problem was that the technology didn't work. All other issues stemmed from this.

**Mistake 2: Staying in EAST while failing at EAST**

The company claimed to be in EAST (innovation/technology) but wasn't actually innovating:

| Claimed | Reality |
|---------|---------|
| Proprietary technology | Used Siemens machines |
| 200+ tests from finger prick | Could do few tests accurately |
| Revolutionary | Mediocre at best |

**Mistake 3: Phase denial at extreme level**

Even as problems mounted, Theranos remained in SUMMER denial:

| Year | Reality | Claimed Phase | Consequence |
|------|---------|---------------|-------------|
| 2013 | Technology failing | SUMMER | Raised more money |
| 2014 | Validation failing | SUMMER | Partnered with Walgreens |
| 2015 | Investigation | SUMMER | Denied everything |

### 6.4. Warning Signs Ignored

| Indicator | Value | Warning |
|-----------|-------|---------|
| SF | 0.15 (too good to be true) | Fraud often creates low SF artificially |
| Transparency | None | Secrecy masked problems |
| Validators | Bought, not earned | Board of famous non-experts |
| CES | 82 (unsupported) | Based on hype, not reality |

### 6.5. Failure Mode Classification

**Primary Failure Mode:** Fraud (special case)
**Secondary Factor:** Phase Denial (extreme)

---

## 7. Case Study 5: Quibi — Wrong Vector for Phase

### 7.1. Company Background

**Quibi** (2018-2020) raised $1.75B for a mobile-only short-form video platform. Launched in April 2020, shut down in December 2020.

| Metric | Value |
|--------|-------|
| Founded | 2018 |
| Launch | April 2020 |
| Shutdown | December 2020 |
| Money raised | $1.75B |
| Subscribers at shutdown | <500,000 |

### 7.2. Trajectory Analysis

| Year | State | Code | CES | SF | Phase |
|------|-------|------|-----|-----|-------|
| 2018 | (WE, EAST, SPRING) | 11 10 11 | 48 | 0.35 | Development |
| 2019 | (WE, EAST, SUMMER) | 11 10 10 | 65 | 0.25 | Pre-launch hype |
| 2020 | (WE, EAST, SUMMER) | 11 10 10 | 70 | 0.20 | Launch |
| 2020 | (WE, EAST, WINTER) | 11 10 00 | 20 | 0.75 | Shutdown |

### 7.3. Critical Mistake Analysis

**Mistake 1: Vector mismatch**

Quibi was in EAST (technology/innovation) but should have been in SOUTH (market/distribution):

| Required for success | Quibi's approach |
|----------------------|-------------------|
| Distribution partnerships | Limited |
| Content acquisition | Expensive, but okay |
| User acquisition | Minimal marketing |
| Viral growth | No social features |

**Mistake 2: Wrong timing (phase misalignment)**

Launched in SPRING/SUMMER transition but behaved like mature business:

| Phase | Should do | Did |
|-------|-----------|-----|
| SPRING | Experiment, iterate | Built massive infrastructure |
| SUMMER | Scale what works | Launched complete product |
| AUTUMN | Optimize | Not applicable |

**Mistake 3: Ignoring market reality**

- Pandemic hit, people were home (not mobile)
- TikTok already dominated short-form
- No compelling reason to use Quibi

### 7.4. Warning Signs Ignored

| Indicator | Value | Warning |
|-----------|-------|---------|
| SF | 0.20 (launch) → 0.75 (shutdown) | Rapid deterioration |
| CES | 70 → 20 | Crash post-launch |
| User feedback | Negative | Ignored |
| Market conditions | Changed | Not adapted |

### 7.5. Failure Mode Classification

**Primary Failure Mode:** Vector Mismatch (EAST when should have been SOUTH)
**Secondary Factor:** Phase Denial (ignoring market reality)

---

## 8. Failure Pattern Synthesis

### 8.1. Common Warning Signs Across Failures

| Warning Sign | Webvan | Kodak | Pets.com | Theranos | Quibi |
|--------------|--------|-------|----------|----------|-------|
| Negative unit economics | ✓ | N/A | ✓ | N/A | ✓ |
| SF > 0.6 | ✓ | ✓ | ✓ | ✓ | ✓ |
| CES drop > 40 points | ✓ | ✓ | ✓ | ✓ | ✓ |
| Phase denial | ✓ | ✓ | ✓ | ✓ | ✓ |
| Premature T_SOUTH | ✓ | ✗ | ✓ | ✗ | ✗ |
| Wrong vector | ✓ | ✓ | ✓ | ✓ | ✓ |

### 8.2. The Failure Timeline

```
Warning Period (SF 0.4-0.6) → Critical Period (SF 0.6-0.8) → Terminal (SF 0.8-1.0)
          6-24 months                 1-6 months                 Days-weeks
```

### 8.3. Survival Factors

What separates companies that recover from WINTER vs. those that don't:

| Factor | Survivors (Apple, Tesla) | Failures |
|--------|--------------------------|----------|
| Cash runway | Preserved | Burned |
| Leadership | Acknowledged crisis | Denial |
| Pivot speed | Fast | Slow |
| Core business | Viable | Broken |
| Investor support | Maintained | Lost |

---

## 9. Prevention Framework

### 9.1. Early Warning System

Monitor these indicators quarterly:

| Metric | Green | Yellow | Red |
|--------|-------|--------|-----|
| CES | >60 | 40-60 | <40 |
| SF | <0.3 | 0.3-0.5 | >0.5 |
| CES trend | + | 0 to -10 | -10+ |
| SF trend | - | 0 to +0.1 | +0.1+ |

### 9.2. Intervention Points

| SF Level | Action |
|----------|--------|
| 0.3-0.4 | Monitor, plan contingencies |
| 0.4-0.5 | Active intervention, review strategy |
| 0.5-0.6 | Emergency board meeting, consider pivot |
| 0.6-0.7 | Immediate action required, cash preservation |
| 0.7+ | Survival mode, all hands on deck |

### 9.3. The Pivot Decision Matrix

| Current State | Option 1 | Option 2 | Option 3 |
|---------------|----------|----------|----------|
| (WE, EAST, AUTUMN) with SF↑ | T_SOUTH (market) | T_WEST (capital) | T_SPRING (reset) |
| (WE, SOUTH, AUTUMN) with SF↑ | T_EAST (innovation) | T_WEST (capital) | T_SPRING (reset) |
| (THEY, *, AUTUMN) with SF↑ | T_* (vector change) | T_SPRING (reset) | — |

---

## 10. Summary: Lessons from Failures

### 10.1. The Five Commandments of Failure Prevention

1. **Thou shalt not scale before unit economics work** — Webvan, Pets.com
2. **Thou shalt pivot when phase changes** — Kodak
3. **Thou shalt match vector to reality** — Quibi
4. **Thou shalt not deny WINTER** — Theranos, Kodak
5. **Thou shalt monitor SF and CES religiously** — All failures ignored this

### 10.2. Key Statistics

| Statistic | Value |
|-----------|-------|
| Average time from WINTER entry to failure | 6-18 months |
| SF threshold for critical danger | >0.6 |
| CES drop preceding failure | 40-60 points |
| Companies that recover from WINTER | ~20% |

### 10.3. Final Insight

**Failure in Economic Geometry is rarely sudden.** The warning signs appear months or years before the end. SF rises, CES falls, and phase denial sets in. The companies that survive are those that:

1. **Monitor their state** continuously
2. **Acknowledge phase changes** immediately
3. **Pivot decisively** when needed
4. **Preserve resources** for the transition

---

*This document provides a structural analysis of startup failures through the lens of Economic Geometry, serving as a reference for understanding collapse patterns and preventing them.*
