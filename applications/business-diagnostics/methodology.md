# METHODOLOGY: Identifying State ω for Real Business

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 8, Section 8.1

---

## 1. Introduction to State Identification

The practical application of Economic Geometry begins with correctly identifying the current state ω of a business. This document provides a systematic methodology for determining the coordinates (WHO, WHERE, WHEN) of any real-world business configuration.

**State Definition:** ω = (A, V, T) where:
- **A (WHO)** — Agency: ME, WE, YOU, THEY
- **V (WHERE)** — Vector: EAST, SOUTH, WEST, NORTH
- **T (WHEN)** — Phase: SPRING, SUMMER, AUTUMN, WINTER

**Binary Encoding:** Each state maps to a unique 6-bit code:
```
|ME|   = |EAST|   = |SPRING|   = |10|
|WE|   = |SOUTH|  = |SUMMER|   = |11|
|YOU|  = |WEST|   = |AUTUMN|   = |01|
|THEY| = |NORTH|  = |WINTER|   = |00|
```

---

## 2. The Identification Framework

### 2.1. Three-Step Process

```
Step 1: Identify AGENCY (WHO)
        ↓
Step 2: Identify VECTOR (WHERE)
        ↓
Step 3: Identify PHASE (WHEN)
        ↓
Step 4: Validate consistency
        ↓
Step 5: Record with confidence level
```

### 2.2. Information Sources

| Source Type | Examples | Reliability |
|-------------|----------|-------------|
| **Primary** | Founders, leadership interviews | High |
| **Documentary** | Business plans, pitch decks | Medium-High |
| **Observational** | Product, website, customer interactions | Medium |
| **Financial** | Revenue models, funding stages | Medium |
| **Market** | Competitor positioning, industry reports | Low-Medium |
| **Historical** | Company timeline, past pivots | Medium |

**Best Practice:** Triangulate from at least three independent sources.

---

## 3. Identifying AGENCY (WHO)

### 3.1. The Four Agency Types

| Agency | Code | Core Question |
|--------|------|---------------|
| **ME** | `10` | Is the business driven by a single individual? |
| **WE** | `11` | Is it driven by a team or partnership? |
| **YOU** | `01` | Is it driven by client/customer demands? |
| **THEY** | `00` | Is it driven by system/platform dynamics? |

### 3.2. ME Agency Indicators

**Definition:** Individual actor — solo founder, sole proprietor, independent professional.

**Diagnostic Questions:**
- Is there a single founder/leader with no formal partners?
- Are key decisions made by one person without consultation?
- Does the business depend on one individual's reputation or skills?
- Is there no formal management team or partnership structure?

**Positive Indicators (ME):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Single founder on paperwork | High | Legal documents |
| "Sole proprietor" legal structure | High | Business registration |
| No co-founders listed | High | Pitch deck, website |
| Key person insurance exists | Medium | Insurance docs |
| "I" language in communications | Medium | Interviews, content |
| Individual portfolio/website | Medium | Online presence |

**Examples:**
- Solo consultant operating independently
- Single inventor with patent
- Freelancer, independent contractor
- Solopreneur running an online business

### 3.3. WE Agency Indicators

**Definition:** Team actor — partnership, co-founding team, organized group.

**Diagnostic Questions:**
- Is there a founding team with multiple members?
- Are decisions made collectively or through structured process?
- Does the business have partners, co-directors, or co-founders?
- Is there shared ownership or equity distribution?

**Positive Indicators (WE):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Multiple founders listed | High | Pitch deck, website |
| Partnership agreement | High | Legal documents |
| Team page with multiple leaders | Medium | Website |
| "We" language in communications | Medium | Interviews, content |
| Shared equity structure | Medium | Cap table |
| Board of directors/partners | Medium | Governance docs |

**Examples:**
- Startup with 2-4 co-founders
- Law firm partnership
- Consulting firm with multiple partners
- Family business run by siblings

### 3.4. YOU Agency Indicators

**Definition:** Client-driven actor — business defined by customer requests, responsive to market demand.

**Diagnostic Questions:**
- Is the business primarily responding to client requests?
- Does a small number of clients define the offering?
- Is there significant custom work vs. productized offerings?
- Does the business follow rather than lead its market?

**Positive Indicators (YOU):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Revenue concentrated in few clients | High | Financials |
| Custom work > 50% of revenue | High | Sales data |
| Client advisory board exists | Medium | Governance |
| "Client-first" messaging | Medium | Marketing |
| Project-based vs. product-based | Medium | Business model |
| High client retention effort | Low | Operations |

**Examples:**
- Agency doing client work
- Custom software development shop
- Professional services firm
- Bespoke manufacturer

### 3.5. THEY Agency Indicators

**Definition:** System-driven actor — platform, marketplace, institution, where the system itself acts.

**Diagnostic Questions:**
- Does the business operate as a platform connecting others?
- Are there network effects (value increases with users)?
- Is there a marketplace, exchange, or ecosystem?
- Is the business institutionalized beyond any individuals?

**Positive Indicators (THEY):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Platform/marketplace business model | High | Business model |
| Network effects present | High | User growth data |
| Institutional structure | High | Legal form |
| Multiple stakeholder groups | Medium | Operations |
| Algorithmic/systemic decision-making | Medium | Technology |
| Brand > individual identities | Medium | Marketing |

**Examples:**
- Marketplace (Airbnb, Uber, eBay)
- Platform (Facebook, iOS, Windows)
- Exchange (NYSE, cryptocurrency exchange)
- Regulatory body (FDA, SEC)
- Standards organization (ISO, IEEE)

### 3.6. Agency Determination Matrix

| Primary Evidence | Secondary Evidence | Conclusion |
|------------------|-------------------|------------|
| Single founder, no partners | "I" language, solo decisions | **ME** |
| Multiple founders, team structure | "We" language, shared equity | **WE** |
| Client concentration, custom work | Client-led roadmap | **YOU** |
| Platform model, network effects | Institutional brand | **THEY** |

**When Ambiguous:** Choose the dominant mode — what drives 51%+ of decision-making and value creation?

---

## 4. Identifying VECTOR (WHERE)

### 4.1. The Four Vector Types

| Vector | Code | Core Question |
|--------|------|---------------|
| **EAST** | `10` | Is value created through innovation/technology? |
| **SOUTH** | `11` | Is value created through market access/distribution? |
| **WEST** | `01` | Is value created through capital/finance? |
| **NORTH** | `00` | Is value created through regulation/authority? |

### 4.2. EAST Vector Indicators

**Definition:** Innovation-driven — technology, R&D, patents, new knowledge.

**Diagnostic Questions:**
- Is the primary value in proprietary technology?
- Are R&D expenses significant relative to revenue?
- Does the business have patents or trade secrets?
- Is the offering technologically novel?

**Positive Indicators (EAST):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Patents filed/granted | High | IP portfolio |
| R&D expense > 15% of revenue | High | Financials |
| Technology as core differentiator | High | Marketing |
| Engineering headcount dominance | Medium | Org chart |
| Technical founders | Medium | Team background |
| Product roadmap driven by innovation | Medium | Strategy docs |

**Examples:**
- Biotech company with patents
- Software company with proprietary algorithm
- Hardware startup with novel design
- R&D lab

### 4.3. SOUTH Vector Indicators

**Definition:** Market-driven — distribution, sales, customers, scale.

**Diagnostic Questions:**
- Is the primary value in reaching customers?
- Are sales and marketing the key functions?
- Does the business excel at distribution?
- Is market share a key metric?

**Positive Indicators (SOUTH):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Sales organization dominance | High | Org chart |
| Marketing expense > R&D | High | Financials |
| Distribution partnerships | High | Partnerships |
| Customer acquisition focus | Medium | Strategy |
| Market share as key metric | Medium | KPIs |
| Sales-led growth | Medium | Growth model |

**Examples:**
- Retail chain
- Direct sales organization
- Marketing agency
- Distribution company
- Franchise operation

### 4.4. WEST Vector Indicators

**Definition:** Capital-driven — finance, investments, ownership, control.

**Diagnostic Questions:**
- Is the primary value in financial engineering?
- Does the business allocate capital to generate returns?
- Is ownership and control a key aspect?
- Are financial metrics paramount?

**Positive Indicators (WEST):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Financial services business model | High | Business model |
| Investment portfolio significant | High | Balance sheet |
| Capital allocation as core competency | High | Strategy |
| Finance headcount significant | Medium | Org chart |
| ROI/IRR as key metrics | Medium | KPIs |
| M&A activity | Medium | Transactions |

**Examples:**
- Bank, hedge fund, VC firm
- Investment holding company
- Private equity firm
- Family office
- Asset manager

### 4.5. NORTH Vector Indicators

**Definition:** Authority-driven — regulation, standards, compliance, power.

**Diagnostic Questions:**
- Is the primary value in regulatory approval?
- Does the business set or enforce standards?
- Is compliance a key service or requirement?
- Does the business derive power from authority?

**Positive Indicators (NORTH):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Regulatory licenses required | High | Operations |
| Standards-setting role | High | Industry position |
| Compliance as service | High | Revenue model |
| Government as primary customer | Medium | Customer base |
| Legal/regulatory expertise core | Medium | Team background |
| Certification authority | Medium | Business model |

**Examples:**
- Regulatory agency
- Standards organization
- Compliance consultancy
- Licensed professional (legal, medical)
- Government contractor

### 4.6. Vector Determination Matrix

| Primary Evidence | Secondary Evidence | Conclusion |
|------------------|-------------------|------------|
| Patents, R&D focus | Technical differentiation | **EAST** |
| Sales organization, market share | Distribution focus | **SOUTH** |
| Financial model, investment focus | Capital allocation | **WEST** |
| Regulatory role, compliance focus | Authority position | **NORTH** |

**When Ambiguous:** Follow the primary value creation mechanism — where does economic value primarily come from?

---

## 5. Identifying PHASE (WHEN)

### 5.1. The Four Phase Types

| Phase | Code | Core Question |
|-------|------|---------------|
| **SPRING** | `10` | Is the business in creation/experimentation mode? |
| **SUMMER** | `11` | Is it in growth/scaling mode? |
| **AUTUMN** | `01` | Is it in optimization/harvesting mode? |
| **WINTER** | `00` | Is it in decline/transformation mode? |

### 5.2. SPRING Phase Indicators

**Definition:** Creation — experimentation, inception, uncertainty, searching for product-market fit.

**Diagnostic Questions:**
- Is the business still finding its model?
- Are there significant experiments ongoing?
- Is revenue small or inconsistent?
- Is the team still small and formative?

**Positive Indicators (SPRING):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Pre-revenue or early revenue | High | Financials |
| Multiple pivots recently | High | History |
| MVP stage | High | Product |
| Small team (<10) | Medium | Org chart |
| Searching for product-market fit | Medium | Strategy |
| High burn rate, low revenue | Medium | Financials |
| Frequent strategy changes | Low | Interviews |

**Examples:**
- Pre-seed/seed startup
- Garage inventor
- New venture in R&D phase
- Corporate innovation lab

### 5.3. SUMMER Phase Indicators

**Definition:** Growth — scaling, expansion, rapid development, capturing market.

**Diagnostic Questions:**
- Is revenue growing rapidly (>20% annually)?
- Is the team expanding quickly?
- Is the focus on capturing market share?
- Are systems being built to handle scale?

**Positive Indicators (SUMMER):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Revenue growth >20% YoY | High | Financials |
| Headcount growth >20% YoY | High | HR data |
| Market share expansion | High | Market data |
| Fundraising for growth | Medium | Financing |
| Expanding geographies/products | Medium | Strategy |
| Building infrastructure | Medium | Operations |
| Hiring across all functions | Medium | HR data |

**Examples:**
- Series A-C startup
- Rapidly expanding retail chain
- Scaling SaaS company
- Growth-stage platform

### 5.4. AUTUMN Phase Indicators

**Definition:** Optimization — maturity, efficiency, harvesting, maximizing returns.

**Diagnostic Questions:**
- Is growth slowing but profits high?
- Is the focus on efficiency and margins?
- Are processes mature and stable?
- Is the business generating cash?

**Positive Indicators (AUTUMN):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Profit margin expansion focus | High | Strategy |
| Revenue growth <15% but profitable | High | Financials |
| Process optimization initiatives | High | Operations |
| Automation projects | Medium | Projects |
| Cost reduction programs | Medium | Strategy |
| Mature management team | Medium | Org chart |
| Dividend or share buybacks | Medium | Financials |

**Examples:**
- Mature public company
- Cash cow business unit
- Established professional firm
- Optimizing franchise network

### 5.5. WINTER Phase Indicators

**Definition:** Decline — crisis, transformation, decay, reinvention.

**Diagnostic Questions:**
- Is revenue declining?
- Is the business losing money or market share?
- Are there turnaround or restructuring efforts?
- Is survival in question?

**Positive Indicators (WINTER):**
| Indicator | Weight | Evidence |
|-----------|--------|----------|
| Revenue decline >10% YoY | High | Financials |
| Losses mounting | High | Financials |
| Layoffs or restructuring | High | HR/Operations |
| Leadership changes | Medium | Org changes |
| Debt covenant issues | Medium | Financials |
| Seeking buyer or merger | Medium | Strategy |
| Asset sales | Medium | Transactions |

**Examples:**
- Company in turnaround
- Declining industry player
- Business facing obsolescence
- Organization in crisis

### 5.6. Phase Determination Matrix

| Primary Evidence | Secondary Evidence | Conclusion |
|------------------|-------------------|------------|
| Pre-revenue, pivoting | Small team, searching | **SPRING** |
| Rapid growth, scaling | Hiring, expanding | **SUMMER** |
| Slowing growth, profit focus | Optimization, efficiency | **AUTUMN** |
| Declining revenue, restructuring | Crisis, layoffs | **WINTER** |

**When Ambiguous:** Look at the dominant organizational energy — what is the primary focus of leadership attention?

---

## 6. The Identification Worksheet

### 6.1. Agency Scorecard

| Question | ME (10) | WE (11) | YOU (01) | THEY (00) |
|----------|---------|---------|----------|-----------|
| Who makes key decisions? | Single leader | Team/consensus | Clients | System/rules |
| Legal structure? | Sole prop | Partnership | Client contracts | Corporation/platform |
| Primary identity? | Individual | Team | Service provider | Platform |
| Language used? | "I" | "We" | "Our clients" | "The platform" |
| **Tally** | | | | |

**Agency = row with highest tally**

### 6.2. Vector Scorecard

| Question | EAST (10) | SOUTH (11) | WEST (01) | NORTH (00) |
|----------|-----------|------------|-----------|------------|
| Primary value source? | Technology | Market access | Capital | Authority |
| Key function? | R&D | Sales/Marketing | Finance | Compliance |
| Key metric? | Innovation | Market share | Returns | Compliance |
| Competitive advantage? | IP | Distribution | Capital | Licenses |
| **Tally** | | | | |

**Vector = row with highest tally**

### 6.3. Phase Scorecard

| Question | SPRING (10) | SUMMER (11) | AUTUMN (01) | WINTER (00) |
|----------|-------------|-------------|-------------|-------------|
| Revenue trend? | Pre/early | Growing >20% | Stable/profitable | Declining |
| Team trend? | Small | Growing | Stable | Shrinking |
| Focus? | Experiment | Scale | Optimize | Survive |
| Energy? | Creative | Expansion | Efficiency | Crisis |
| **Tally** | | | | |

**Phase = row with highest tally**

---

## 7. Handling Ambiguity and Edge Cases

### 7.1. Mixed Agency

Some businesses exhibit characteristics of multiple agency types:

**Example:** A platform (THEY) run by a founding team (WE)
- **Rule:** Dominant agency = where primary value creation occurs
- **Test:** If the platform were automated, would it still function? If yes → THEY; if requires team → WE

**Example:** A consultancy (YOU) with a strong founder (ME)
- **Rule:** If the founder left, would the business continue? If yes → YOU; if no → ME

### 7.2. Mixed Vector

**Example:** Tech company with strong sales (EAST + SOUTH)
- **Rule:** Primary vector = where competitive advantage lies
- **Test:** Is the technology unique and defensible? If yes → EAST; is distribution the key barrier? If yes → SOUTH

**Example:** Financial services with regulatory focus (WEST + NORTH)
- **Rule:** Follow the revenue — where do profits primarily come from?

### 7.3. Phase Boundaries

**Example:** Late SUMMER / early AUTUMN
- **Rule:** Look at leadership attention — if focused on growth levers → SUMMER; if focused on efficiency levers → AUTUMN

**Example:** Late AUTUMN / early WINTER
- **Rule:** Is decline reversible? If planning turnaround → AUTUMN; if in active crisis → WINTER

### 7.4. Confidence Levels

| Confidence | Meaning | Action |
|------------|---------|--------|
| **High (90%+)** | All indicators align | Use for strategic decisions |
| **Medium (70-90%)** | Most indicators align, some ambiguity | Note uncertainty, monitor |
| **Low (<70%)** | Significant ambiguity | Gather more data, revisit |

**Record as:** ω = (A, V, T) with confidence [H/M/L]

---

## 8. Validation Techniques

### 8.1. Triangulation

Compare identification from multiple sources:
- Founder interviews
- Document review
- Customer perspectives
- Investor views
- Market positioning

**Consensus increases confidence.**

### 8.2. Temporal Validation

Track state over time:
- Is the identified state stable?
- Does it change with major events?
- Does it align with observable trajectory?

### 8.3. Peer Comparison

Compare with similar businesses:
- What state are competitors in?
- Is this consistent with industry position?

### 8.4. CES/SF Consistency Check

After identifying ω, calculate CES and SF:
- Does the score seem reasonable given business performance?
- Extreme values should prompt re-examination

---

## 9. Common Identification Mistakes

| Mistake | Correction |
|---------|------------|
| Confusing ME with WE (single founder with employees) | Employees ≠ team — look at decision-making |
| Confusing YOU with THEY (platform vs. client-driven) | Platform has network effects; client-driven is service |
| EAST vs. SOUTH (tech vs. market) | Follow the advantage — where is the moat? |
| SUMMER vs. AUTUMN (growth vs. optimization) | Look at leadership focus, not just growth rate |
| WINTER misdiagnosis (treating as AUTUMN) | Declining revenue + losses + restructuring = WINTER |

---

## 10. Quick Reference Card

### Agency Identification

| If... | Then... |
|-------|---------|
| Solo founder, individual decision-making | **ME (10)** |
| Team, partnership, collective decisions | **WE (11)** |
| Client-driven, custom work | **YOU (01)** |
| Platform, marketplace, system | **THEY (00)** |

### Vector Identification

| If... | Then... |
|-------|---------|
| Technology, R&D, patents | **EAST (10)** |
| Market, sales, distribution | **SOUTH (11)** |
| Capital, finance, investments | **WEST (01)** |
| Regulation, authority, compliance | **NORTH (00)** |

### Phase Identification

| If... | Then... |
|-------|---------|
| Pre-revenue, experimenting, pivoting | **SPRING (10)** |
| Rapid growth, scaling, hiring | **SUMMER (11)** |
| Slowing growth, profit focus, efficiency | **AUTUMN (01)** |
| Declining revenue, crisis, restructuring | **WINTER (00)** |

---

## 11. Worked Examples

### Example 1: Early-Stage Tech Startup

**Company:** 2 co-founders building a SaaS product, pre-revenue, raising seed round, still figuring out product-market fit.

**Analysis:**
- Agency: WE (two co-founders, team decisions)
- Vector: EAST (building technology, R&D focus)
- Phase: SPRING (pre-revenue, experimenting)

**Result:** ω = (WE, EAST, SPRING) = 11 10 11
**Confidence:** High

### Example 2: Established Consulting Firm

**Company:** 50-partner firm, stable revenue, profitable, focus on efficiency and utilization rates, mature market.

**Analysis:**
- Agency: WE (partnership structure)
- Vector: SOUTH? Wait — consulting sells expertise (EAST?) Actually consulting sells market access? No — consulting sells expertise and advice → closer to YOU? But structure is WE.

Let's think carefully:
- Agency: WE (partnership)
- Vector: YOU? Actually consulting firms sell expertise (EAST-like) but through relationships (SOUTH-like). Primary value is in client relationships → **SOUTH**
- Phase: AUTUMN (optimizing utilization, mature)

**Result:** ω = (WE, SOUTH, AUTUMN) = 11 11 01
**Confidence:** Medium (vector ambiguous)

### Example 3: Failing Retail Chain

**Company:** National retailer, sales down 15% for 3 years, closing stores, laying off staff, seeking buyer.

**Analysis:**
- Agency: THEY (institutional, system-driven)
- Vector: SOUTH (retail, market-facing)
- Phase: WINTER (declining, restructuring)

**Result:** ω = (THEY, SOUTH, WINTER) = 00 11 00
**Confidence:** High

---

## 12. Summary

| Step | Task | Output |
|------|------|--------|
| 1 | Identify Agency | ME (10), WE (11), YOU (01), THEY (00) |
| 2 | Identify Vector | EAST (10), SOUTH (11), WEST (01), NORTH (00) |
| 3 | Identify Phase | SPRING (10), SUMMER (11), AUTUMN (01), WINTER (00) |
| 4 | Combine | ω = (A, V, T) |
| 5 | Encode | 6-bit binary code |
| 6 | Validate | Check consistency, confidence |

**Key Principle:** The state ω is not a permanent label but a snapshot. Businesses evolve through Ω over time. Regular re-assessment is essential.

---

*This document provides the methodology for identifying economic states in real businesses, serving as a practical guide for applying Economic Geometry.*
