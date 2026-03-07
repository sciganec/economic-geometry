# QUADRANT 2: WE Agency States (WHO = WE)

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Appendix B, Section 3.4

---

## 1. Introduction to Quadrant 2

**Quadrant 2** contains all states where the agency dimension is **WE** (code `11`). These configurations represent business activities driven by **teams, partnerships, and collective agents** — startups with co-founders, professional partnerships, organized groups, and collaborative enterprises.

**Key Characteristics of WE Agency:**
- **Decision-making:** Collaborative, consensus-based, structured
- **Accountability:** Shared responsibility, distributed
- **Resources:** Combined team capabilities, pooled resources
- **Flexibility:** Moderate adaptability, some inertia
- **Scale:** Scalable through team expansion

**WE Code:** `11`
- Bit 1: `1` = collective? Wait — correction:
- Bit 1: `1` = individual? No — WE is collective
- Let's clarify: In canonical encoding:
  - Bit 1: `1` = individual (ME, YOU), `0` = collective (WE, THEY)
  - Bit 2: `0` = active (ME, WE), `1` = passive (YOU, THEY)

So WE = `11` means:
- Bit 1: `1`? This is inconsistent — WE should be collective (0) but code is 11.

**IMPORTANT CORRECTION:** The canonical encoding is based on the mnemonic, not binary logic. WE = `11` by convention, regardless of bit interpretation.

---

## 2. Complete WE State Table

| # | Code | Vector | Phase | State Name | CES | SF |
|---|------|--------|-------|------------|-----|-----|
| 48 | 11 00 00 | NORTH | WINTER | Dissolution Committee | 15-30 | 0.6-0.8 |
| 49 | 11 00 01 | NORTH | AUTUMN | Regulatory Commission | 50-65 | 0.2-0.4 |
| 50 | 11 00 10 | NORTH | SUMMER | Trade Association | 55-70 | 0.2-0.3 |
| 51 | 11 00 11 | NORTH | SPRING | NGO / Activist Group | 30-45 | 0.3-0.5 |
| 52 | 11 01 00 | WEST | WINTER | Liquidation Fund | 10-25 | 0.7-0.9 |
| 53 | 11 01 01 | WEST | AUTUMN | Private Equity | 60-75 | 0.2-0.4 |
| 54 | 11 01 10 | WEST | SUMMER | Hedge Fund / VC Fund | 65-80 | 0.1-0.3 |
| 55 | 11 01 11 | WEST | SPRING | New Investment Fund | 35-50 | 0.3-0.5 |
| 56 | 11 10 00 | EAST | WINTER | Tech Outsourcer | 20-35 | 0.5-0.7 |
| 57 | 11 10 01 | EAST | AUTUMN | Tech Giant (Optimizing) | 65-80 | 0.2-0.3 |
| 58 | 11 10 10 | EAST | SUMMER | Tech Startup (Scaling) | 75-90 | 0.1-0.2 |
| 59 | 11 10 11 | EAST | SPRING | R&D Lab / Early Startup | 45-60 | 0.2-0.4 |
| 60 | 11 11 00 | SOUTH | WINTER | Market Exit Team | 15-30 | 0.6-0.8 |
| 61 | 11 11 01 | SOUTH | AUTUMN | Consulting Firm | 60-75 | 0.2-0.3 |
| 62 | 11 11 10 | SOUTH | SUMMER | Scaling Enterprise | 75-90 | 0.1-0.2 |
| 63 | 11 11 11 | SOUTH | SPRING | Market Entrant | 40-55 | 0.2-0.4 |

---

## 3. Detailed State Profiles

### 3.1. WE × NORTH × WINTER (11 00 00)
**Name:** Dissolution Committee

| Property | Value |
|----------|-------|
| **Binary Code** | 11 00 00 |
| **Decimal** | 48 |
| **State** | (WE, NORTH, WINTER) |
| **Description** | Team winding down regulatory or government operations. Closing agencies, ending programs, dissolving organizations. |
| **Example** | Transition team for agency closure, government shutdown task force |
| **CES Range** | 15-30 |
| **Typical CES** | 22 |
| **SF Range** | 0.6-0.8 |
| **Typical SF** | 0.70 |
| **Risk Profile** | Political challenges, incomplete closure, public backlash |
| **Monetization** | Wind-down contracts, severance management |
| **Typical Trajectory** | T_THEY → (THEY, NORTH, WINTER) or T_SPRING → (WE, NORTH, SPRING) |
| **CES Gain Potential** | +23 (to SPRING) |

### 3.2. WE × NORTH × AUTUMN (11 00 01)
**Name:** Regulatory Commission

| Property | Value |
|----------|-------|
| **Binary Code** | 11 00 01 |
| **Decimal** | 49 |
| **State** | (WE, NORTH, AUTUMN) |
| **Description** | Team running established regulatory body. Efficient enforcement, stable operations, mature processes. |
| **Example** | Antimonopoly committee, utility commission, licensing board |
| **CES Range** | 50-65 |
| **Typical CES** | 58 |
| **SF Range** | 0.2-0.4 |
| **Typical SF** | 0.30 |
| **Risk Profile** | Capture by industry, bureaucratic inefficiency, political interference |
| **Monetization** | Fees, fines, licensing revenue |
| **Typical Trajectory** | T_WINTER → (WE, NORTH, WINTER) or T_WEST → (WE, WEST, AUTUMN) |
| **CES Gain Potential** | +7 (to SUMMER) |

### 3.3. WE × NORTH × SUMMER (11 00 10)
**Name:** Trade Association

| Property | Value |
|----------|-------|
| **Binary Code** | 11 00 10 |
| **Decimal** | 50 |
| **State** | (WE, NORTH, SUMMER) |
| **Description** | Team building influence in regulatory domain. Expanding membership, growing power, shaping policy. |
| **Example** | Industry association, lobbying group, professional society |
| **CES Range** | 55-70 |
| **Typical CES** | 62 |
| **SF Range** | 0.2-0.3 |
| **Typical SF** | 0.25 |
| **Risk Profile** | Overreach, public backlash, member conflicts |
| **Monetization** | Membership dues, lobbying fees, event revenue |
| **Typical Trajectory** | T_AUTUMN → (WE, NORTH, AUTUMN) or T_SOUTH → (WE, SOUTH, SUMMER) |
| **CES Gain Potential** | +20 (to SOUTH,SUMMER) |

### 3.4. WE × NORTH × SPRING (11 00 11)
**Name:** NGO / Activist Group

| Property | Value |
|----------|-------|
| **Binary Code** | 11 00 11 |
| **Decimal** | 51 |
| **State** | (WE, NORTH, SPRING) |
| **Description** | Team forming to influence regulations or advocate for change. Building initial campaign, organizing, seeking impact. |
| **Example** | Newly formed non-profit, activist organization, advocacy group |
| **CES Range** | 30-45 |
| **Typical CES** | 38 |
| **SF Range** | 0.3-0.5 |
| **Typical SF** | 0.40 |
| **Risk Profile** | Failure to gain traction, funding challenges, internal disputes |
| **Monetization** | Grants, donations, foundation support |
| **Typical Trajectory** | T_SUMMER → (WE, NORTH, SUMMER) or T_EAST → (WE, EAST, SPRING) |
| **CES Gain Potential** | +24 (to SUMMER) |

---

### 3.5. WE × WEST × WINTER (11 01 00)
**Name:** Liquidation Fund

| Property | Value |
|----------|-------|
| **Binary Code** | 11 01 00 |
| **Decimal** | 52 |
| **State** | (WE, WEST, WINTER) |
| **Description** | Team winding down investments, closing positions, returning capital to investors. |
| **Example** | Fund in wind-down, liquidation team, distressed asset manager |
| **CES Range** | 10-25 |
| **Typical CES** | 18 |
| **SF Range** | 0.7-0.9 |
| **Typical SF** | 0.80 |
| **Risk Profile** | Losses, investor lawsuits, reputational damage |
| **Monetization** | Liquidation fees, carry (if any remains) |
| **Typical Trajectory** | T_THEY → (THEY, WEST, WINTER) or T_SPRING → (WE, WEST, SPRING) |
| **CES Gain Potential** | +27 (to SPRING) |

### 3.6. WE × WEST × AUTUMN (11 01 01)
**Name:** Private Equity

| Property | Value |
|----------|-------|
| **Binary Code** | 11 01 01 |
| **Decimal** | 53 |
| **State** | (WE, WEST, AUTUMN) |
| **Description** | Team managing mature investments. Harvesting returns, optimizing portfolio companies, preparing exits. |
| **Example** | Private equity firm, buyout fund, mezzanine fund |
| **CES Range** | 60-75 |
| **Typical CES** | 68 |
| **SF Range** | 0.2-0.4 |
| **Typical SF** | 0.30 |
| **Risk Profile** | Economic downturns, bad acquisitions, exit timing |
| **Monetization** | Carried interest, management fees, deal fees |
| **Typical Trajectory** | T_WINTER → (WE, WEST, WINTER) or T_NORTH → (WE, NORTH, AUTUMN) |
| **CES Gain Potential** | +4 (to SUMMER) |

### 3.7. WE × WEST × SUMMER (11 01 10)
**Name:** Hedge Fund / VC Fund

| Property | Value |
|----------|-------|
| **Binary Code** | 11 01 10 |
| **Decimal** | 54 |
| **State** | (WE, WEST, SUMMER) |
| **Description** | Team actively investing and growing capital. Seeking returns, deploying capital, expanding portfolio. |
| **Example** | Venture capital firm, hedge fund, growth equity fund |
| **CES Range** | 65-80 |
| **Typical CES** | 72 |
| **SF Range** | 0.1-0.3 |
| **Typical SF** | 0.20 |
| **Risk Profile** | Market volatility, bad investments, fundraising pressure |
| **Monetization** | Management fees, carried interest |
| **Typical Trajectory** | T_AUTUMN → (WE, WEST, AUTUMN) or T_EAST → (WE, EAST, SUMMER) |
| **CES Gain Potential** | +10 (to EAST,SUMMER) |

### 3.8. WE × WEST × SPRING (11 01 11)
**Name:** New Investment Fund

| Property | Value |
|----------|-------|
| **Binary Code** | 11 01 11 |
| **Decimal** | 55 |
| **State** | (WE, WEST, SPRING) |
| **Description** | Team forming new fund. Raising capital, defining strategy, seeking first investments, building track record. |
| **Example** | New VC fund raising first fund, emerging manager |
| **CES Range** | 35-50 |
| **Typical CES** | 42 |
| **SF Range** | 0.3-0.5 |
| **Typical SF** | 0.40 |
| **Risk Profile** | Failure to raise, poor first investments, team dynamics |
| **Monetization** | Initial management fees, founder commitments |
| **Typical Trajectory** | T_SUMMER → (WE, WEST, SUMMER) or T_SOUTH → (WE, SOUTH, SPRING) |
| **CES Gain Potential** | +30 (to SUMMER) |

---

### 3.9. WE × EAST × WINTER (11 10 00)
**Name:** Tech Outsourcer

| Property | Value |
|----------|-------|
| **Binary Code** | 11 10 00 |
| **Decimal** | 56 |
| **State** | (WE, EAST, WINTER) |
| **Description** | Team maintaining legacy technology. Supporting declining systems, providing migration services, winding down. |
| **Example** | COBOL maintenance team, legacy system support, technology transition team |
| **CES Range** | 20-35 |
| **Typical CES** | 28 |
| **SF Range** | 0.5-0.7 |
| **Typical SF** | 0.60 |
| **Risk Profile** | Obsolescence, skill irrelevance, client attrition |
| **Monetization** | Maintenance contracts, migration services |
| **Typical Trajectory** | T_THEY → (THEY, EAST, WINTER) or T_SPRING → (WE, EAST, SPRING) |
| **CES Gain Potential** | +27 (to SPRING) |

### 3.10. WE × EAST × AUTUMN (11 10 01)
**Name:** Tech Giant (Optimizing)

| Property | Value |
|----------|-------|
| **Binary Code** | 11 10 01 |
| **Decimal** | 57 |
| **State** | (WE, EAST, AUTUMN) |
| **Description** | Large technology company optimizing mature products. Maximizing revenue from existing technology, extending product life. |
| **Example** | Microsoft (Windows division), Oracle, SAP, mature software company |
| **CES Range** | 65-80 |
| **Typical CES** | 72 |
| **SF Range** | 0.2-0.3 |
| **Typical SF** | 0.25 |
| **Risk Profile** | Disruption, missed innovation, competition from agile startups |
| **Monetization** | Licensing, enterprise sales, maintenance fees |
| **Typical Trajectory** | T_WINTER → (WE, EAST, WINTER) or T_WEST → (WE, WEST, AUTUMN) |
| **CES Gain Potential** | +10 (to SUMMER) |

### 3.11. WE × EAST × SUMMER (11 10 10)
**Name:** Tech Startup (Scaling)

| Property | Value |
|----------|-------|
| **Binary Code** | 11 10 10 |
| **Decimal** | 58 |
| **State** | (WE, EAST, SUMMER) |
| **Description** | Technology company in growth phase. Scaling product, team, and users. Rapid expansion, product-market fit achieved. |
| **Example** | Series B/C startup, growing SaaS company, scaling tech firm |
| **CES Range** | 75-90 |
| **Typical CES** | 82 |
| **SF Range** | 0.1-0.2 |
| **Typical SF** | 0.15 |
| **Risk Profile** | Scaling challenges, competition, hiring difficulties, cash management |
| **Monetization** | Subscriptions, licensing, enterprise contracts |
| **Typical Trajectory** | T_AUTUMN → (WE, EAST, AUTUMN) or T_SOUTH → (WE, SOUTH, SUMMER) |
| **CES Gain Potential** | +0 (peak state) to +8 (to SOUTH,SUMMER) |

### 3.12. WE × EAST × SPRING (11 10 11)
**Name:** R&D Lab / Early Startup

| Property | Value |
|----------|-------|
| **Binary Code** | 11 10 11 |
| **Decimal** | 59 |
| **State** | (WE, EAST, SPRING) |
| **Description** | Team developing new technology. Experimenting, prototyping, seeking product-market fit, early stage. |
| **Example** | Early-stage startup, research lab, innovation team, skunkworks |
| **CES Range** | 45-60 |
| **Typical CES** | 52 |
| **SF Range** | 0.2-0.4 |
| **Typical SF** | 0.30 |
| **Risk Profile** | Technical failure, no market, funding challenges |
| **Monetization** | Grants, seed funding, R&D contracts |
| **Typical Trajectory** | T_SUMMER → (WE, EAST, SUMMER) or T_SOUTH → (WE, SOUTH, SPRING) |
| **CES Gain Potential** | +30 (to SUMMER) |

---

### 3.13. WE × SOUTH × WINTER (11 11 00)
**Name:** Market Exit Team

| Property | Value |
|----------|-------|
| **Binary Code** | 11 11 00 |
| **Decimal** | 60 |
| **State** | (WE, SOUTH, WINTER) |
| **Description** | Team winding down market operations. Closing stores, exiting regions, liquidating inventory. |
| **Example** | Retail chain liquidation team, market withdrawal task force |
| **CES Range** | 15-30 |
| **Typical CES** | 22 |
| **SF Range** | 0.6-0.8 |
| **Typical SF** | 0.70 |
| **Risk Profile** | Losses, reputational damage, employee issues |
| **Monetization** | Liquidation sales, severance management |
| **Typical Trajectory** | T_THEY → (THEY, SOUTH, WINTER) or T_SPRING → (WE, SOUTH, SPRING) |
| **CES Gain Potential** | +26 (to SPRING) |

### 3.14. WE × SOUTH × AUTUMN (11 11 01)
**Name:** Consulting Firm

| Property | Value |
|----------|-------|
| **Binary Code** | 11 11 01 |
| **Decimal** | 61 |
| **State** | (WE, SOUTH, AUTUMN) |
| **Description** | Team optimizing market operations for clients. Mature, efficient, expertise-based professional services. |
| **Example** | McKinsey, BCG, Bain, established consulting firm |
| **CES Range** | 60-75 |
| **Typical CES** | 68 |
| **SF Range** | 0.2-0.3 |
| **Typical SF** | 0.25 |
| **Risk Profile** | Reputation dependence, competition, partner retention |
| **Monetization** | Consulting fees, retainers, project-based billing |
| **Typical Trajectory** | T_WINTER → (WE, SOUTH, WINTER) or T_WEST → (WE, WEST, AUTUMN) |
| **CES Gain Potential** | +14 (to SUMMER) |

### 3.15. WE × SOUTH × SUMMER (11 11 10)
**Name:** Scaling Enterprise

| Property | Value |
|----------|-------|
| **Binary Code** | 11 11 10 |
| **Decimal** | 62 |
| **State** | (WE, SOUTH, SUMMER) |
| **Description** | Team rapidly expanding market presence. Opening new locations, acquiring customers, scaling operations. |
| **Example** | Franchise network, retail chain in growth, expanding service business |
| **CES Range** | 75-90 |
| **Typical CES** | 82 |
| **SF Range** | 0.1-0.2 |
| **Typical SF** | 0.15 |
| **Risk Profile** | Overexpansion, quality control, culture dilution |
| **Monetization** | Sales, franchise fees, service revenue |
| **Typical Trajectory** | T_AUTUMN → (WE, SOUTH, AUTUMN) or T_EAST → (WE, EAST, SUMMER) |
| **CES Gain Potential** | +0 (peak state) |

### 3.16. WE × SOUTH × SPRING (11 11 11)
**Name:** Market Entrant

| Property | Value |
|----------|-------|
| **Binary Code** | 11 11 11 |
| **Decimal** | 63 |
| **State** | (WE, SOUTH, SPRING) |
| **Description** | Team entering new market. Finding first customers, establishing presence, building brand. |
| **Example** | Team launching in new geography, market entry team |
| **CES Range** | 40-55 |
| **Typical CES** | 48 |
| **SF Range** | 0.2-0.4 |
| **Typical SF** | 0.30 |
| **Risk Profile** | Market rejection, cultural barriers, competitive response |
| **Monetization** | Initial sales, market development funds |
| **Typical Trajectory** | T_SUMMER → (WE, SOUTH, SUMMER) or T_EAST → (WE, EAST, SPRING) |
| **CES Gain Potential** | +34 (to SUMMER) |

---

## 4. WE State Patterns

### 4.1. CES by Phase (WE Agency)

| Phase | Avg CES | Range | Best Vector |
|-------|---------|-------|-------------|
| **SPRING** | 45 | 30-55 | EAST (52) |
| **SUMMER** | 79 | 65-90 | EAST/SOUTH (82) |
| **AUTUMN** | 66 | 50-80 | EAST/WEST (72) |
| **WINTER** | 22 | 10-35 | EAST (28) highest |

### 4.2. SF by Phase (WE Agency)

| Phase | Avg SF | Range | Best Vector |
|-------|--------|-------|-------------|
| **SPRING** | 0.35 | 0.2-0.5 | EAST (0.30) |
| **SUMMER** | 0.17 | 0.1-0.3 | EAST/SOUTH (0.15) |
| **AUTUMN** | 0.26 | 0.2-0.4 | EAST (0.25) |
| **WINTER** | 0.70 | 0.5-0.9 | EAST (0.60) lowest |

### 4.3. CES by Vector (WE Agency)

| Vector | Avg CES | Best Phase |
|--------|---------|------------|
| **EAST** | 59 | SUMMER (82) |
| **SOUTH** | 55 | SUMMER (82) |
| **WEST** | 50 | SUMMER (72) |
| **NORTH** | 45 | SUMMER (62) |

---

## 5. Top WE States (Highest CES)

| Rank | State | CES | SF | Description |
|------|-------|-----|-----|-------------|
| 1 | (WE, EAST, SUMMER) | 82 | 0.15 | Tech Startup (Scaling) |
| 1 | (WE, SOUTH, SUMMER) | 82 | 0.15 | Scaling Enterprise |
| 3 | (WE, WEST, SUMMER) | 72 | 0.20 | Hedge Fund / VC Fund |
| 3 | (WE, EAST, AUTUMN) | 72 | 0.25 | Tech Giant (Optimizing) |
| 5 | (WE, WEST, AUTUMN) | 68 | 0.30 | Private Equity |
| 5 | (WE, SOUTH, AUTUMN) | 68 | 0.25 | Consulting Firm |
| 7 | (WE, NORTH, SUMMER) | 62 | 0.25 | Trade Association |

---

## 6. Strategic Trajectories for WE States

### 6.1. The Tech Startup Path (EAST Vector)

```
(WE, EAST, SPRING) ─T_SUMMER→ (WE, EAST, SUMMER) ─T_AUTUMN→ (WE, EAST, AUTUMN) ─T_WINTER→ (WE, EAST, WINTER)
      CES:52                CES:82                 CES:72                  CES:28
       SF:0.30               SF:0.15                SF:0.25                 SF:0.60
```

**Alternative Branch:** T_SOUTH from SUMMER → (WE, SOUTH, SUMMER) [CES 82]

### 6.2. The Market Expansion Path (SOUTH Vector)

```
(WE, SOUTH, SPRING) ─T_SUMMER→ (WE, SOUTH, SUMMER) ─T_AUTUMN→ (WE, SOUTH, AUTUMN) ─T_WEST→ (WE, WEST, AUTUMN)
      CES:48                     CES:82                  CES:68                   CES:68
       SF:0.30                    SF:0.15                 SF:0.25                  SF:0.30
```

### 6.3. The Investment Path (WEST Vector)

```
(WE, WEST, SPRING) ─T_SUMMER→ (WE, WEST, SUMMER) ─T_AUTUMN→ (WE, WEST, AUTUMN) ─T_NORTH→ (WE, NORTH, AUTUMN)
      CES:42                     CES:72                  CES:68                   CES:58
       SF:0.40                    SF:0.20                 SF:0.30                  SF:0.30
```

### 6.4. The Institutional Path (NORTH Vector)

```
(WE, NORTH, SPRING) ─T_SUMMER→ (WE, NORTH, SUMMER) ─T_AUTUMN→ (WE, NORTH, AUTUMN) ─T_WINTER→ (WE, NORTH, WINTER)
      CES:38                        CES:62                  CES:58                   CES:22
       SF:0.40                       SF:0.25                 SF:0.30                  SF:0.70
```

---

## 7. Peak Performance States

### 7.1. The "Sweet Spot" — SUMMER Phase

All SUMMER phase WE states have CES > 60, with EAST and SOUTH vectors reaching 82:

| State | CES | SF | Characteristics |
|-------|-----|-----|-----------------|
| (WE, EAST, SUMMER) | 82 | 0.15 | Product-market fit, scaling tech |
| (WE, SOUTH, SUMMER) | 82 | 0.15 | Market traction, expanding reach |
| (WE, WEST, SUMMER) | 72 | 0.20 | Strong fundraising, deploying capital |
| (WE, NORTH, SUMMER) | 62 | 0.25 | Growing influence, membership |

### 7.2. Optimal Transition Points

| Current State | Optimal Next | Timing | CES Gain |
|---------------|--------------|--------|----------|
| (WE, EAST, SPRING) | T_SUMMER | When product-market fit achieved | +30 |
| (WE, SOUTH, SPRING) | T_SUMMER | When first customers validated | +34 |
| (WE, EAST, SUMMER) | T_SOUTH | When technology mature, market opportunity | +0 (diversification) |
| (WE, SOUTH, SUMMER) | T_AUTUMN | When growth slows, focus on efficiency | -14 |

---

## 8. WE State Summary

| Metric | Value |
|--------|-------|
| **Total WE States** | 16 |
| **Highest CES** | 82 (EAST,SUMMER and SOUTH,SUMMER) |
| **Lowest CES** | 18 (WEST,WINTER) |
| **Average CES** | 54.5 |
| **Lowest SF** | 0.15 (EAST,SUMMER and SOUTH,SUMMER) |
| **Highest SF** | 0.80 (WEST,WINTER) |
| **Average SF** | 0.33 |
| **Best Phase** | SUMMER (avg CES 79, SF 0.17) |
| **Best Vector** | EAST (avg CES 59) |

**Key Insight for WE Agency:** Teams reach their highest performance in SUMMER phase, particularly when focused on technology (EAST) or market expansion (SOUTH). The critical challenge is managing the transition from SUMMER to AUTUMN — optimizing without losing momentum — and avoiding the high-friction WINTER states.

**WE Advantage:** Teams have access to the highest CES states in the entire space (82), but also face significant friction in WINTER. The key to sustained success is timely transitions and avoiding overstaying in any phase.

---

*This document provides complete analysis of Quadrant 2 (WE agency states) in Economic Geometry, serving as a reference for team-based business configurations.*
