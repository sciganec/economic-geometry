# SUBIT-64 CATALOG: Complete Atlas of Economic States

**Document Version:** 1.0 (FINAL, VERIFIED)
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Appendix B

---

## 1. Introduction to the Catalog

This document provides a complete catalog of all 64 states in the economic state space Ω = A × V × T. Each state is uniquely identified by its 6-bit binary code and its triple (WHO, WHERE, WHEN). For each state, we provide:

- **Binary code** (6 bits)
- **Decimal identifier** (0-63)
- **State triple** (A, V, T)
- **Name** — canonical archetypal name
- **Description** — brief explanation of the configuration
- **Example** — real-world business example
- **CES range** — typical Capital Efficiency Score
- **SF range** — typical Structural Friction
- **Risk profile** — primary risks
- **Monetization** — typical revenue models
- **Typical trajectory** — common next states

---

## 2. Canonical Encoding Reference

```
|ME|   = |EAST|   = |SPRING|   = |10|
|WE|   = |SOUTH|  = |SUMMER|   = |11|
|YOU|  = |WEST|   = |AUTUMN|   = |01|
|THEY| = |NORTH|  = |WINTER|   = |00|
```

### Decoding Table

| Bits | WHO | WHERE | WHEN |
|------|-----|-------|------|
| `10` | ME | EAST | SPRING |
| `11` | WE | SOUTH | SUMMER |
| `01` | YOU | WEST | AUTUMN |
| `00` | THEY | NORTH | WINTER |

---

## 3. Complete State Catalog

### 3.1. THEY States (A = 00)

#### THEY × NORTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 00 00 00 |
| **Decimal** | 0 |
| **State** | (THEY, NORTH, WINTER) |
| **Name** | Dying Institution |
| **Description** | A systemic entity in the regulatory domain during decline phase. Bureaucracy outliving its purpose, facing dissolution. |
| **Example** | Liquidated government ministry, obsolete standards body |
| **CES** | 0-20 |
| **SF** | 0.8-1.0 |
| **Risk** | Extinction, irrelevance |
| **Monetization** | None (winding down) |
| **Typical trajectory** | T_ME → (ME, NORTH, WINTER) or T_EAST → (THEY, EAST, WINTER) or T_SPRING → (THEY, NORTH, SPRING) |

#### THEY × NORTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 00 00 01 |
| **Decimal** | 1 |
| **State** | (THEY, NORTH, AUTUMN) |
| **Name** | Mature Regulator |
| **Description** | Established regulatory body in optimization phase. Efficient but potentially ossified. |
| **Example** | FDA, SEC, mature standards organization |
| **CES** | 45-60 |
| **SF** | 0.3-0.5 |
| **Risk** | Stagnation, capture by industry |
| **Monetization** | Fees, fines, compliance services |
| **Typical trajectory** | T_WINTER → (THEY, NORTH, WINTER) or T_SOUTH → (THEY, SOUTH, AUTUMN) |

#### THEY × NORTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 00 00 10 |
| **Decimal** | 2 |
| **State** | (THEY, NORTH, SUMMER) |
| **Name** | Growing Regulator |
| **Description** | Regulatory body expanding its influence and scope. Gaining power and jurisdiction. |
| **Example** | Newly empowered agency, expanding standards body |
| **CES** | 55-70 |
| **SF** | 0.2-0.4 |
| **Risk** | Overreach, backlash |
| **Monetization** | Expanding fee base, new regulations |
| **Typical trajectory** | T_AUTUMN → (THEY, NORTH, AUTUMN) or T_WEST → (THEY, WEST, SUMMER) |

#### THEY × NORTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 00 00 11 |
| **Decimal** | 3 |
| **State** | (THEY, NORTH, SPRING) |
| **Name** | New Regulator |
| **Description** | Newly formed regulatory body or standards organization. Creating rules, establishing authority. |
| **Example** | New government agency, newly formed industry standards body |
| **CES** | 40-55 |
| **SF** | 0.3-0.5 |
| **Risk** | Irrelevance, lack of authority |
| **Monetization** | Initial fees, grants |
| **Typical trajectory** | T_SUMMER → (THEY, NORTH, SUMMER) or T_EAST → (THEY, EAST, SPRING) |

#### THEY × WEST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 00 01 00 |
| **Decimal** | 4 |
| **State** | (THEY, WEST, WINTER) |
| **Name** | Collapsed Financial Institution |
| **Description** | Systemic financial entity in terminal decline. Bankruptcy, liquidation. |
| **Example** | Lehman Brothers 2008, failed central bank |
| **CES** | 0-15 |
| **SF** | 0.8-1.0 |
| **Risk** | Complete loss |
| **Monetization** | None (receivership) |
| **Typical trajectory** | T_ME → (ME, WEST, WINTER) or T_SPRING → (THEY, WEST, SPRING) |

#### THEY × WEST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 00 01 01 |
| **Decimal** | 5 |
| **State** | (THEY, WEST, AUTUMN) |
| **Name** | Mature Financial Institution |
| **Description** | Established bank, exchange, or fund in optimization phase. Efficient capital management. |
| **Example** | JPMorgan Chase, NYSE, BlackRock |
| **CES** | 60-75 |
| **SF** | 0.2-0.4 |
| **Risk** | Systemic risk, regulatory change |
| **Monetization** | Interest, fees, asset management |
| **Typical trajectory** | T_WINTER → (THEY, WEST, WINTER) or T_NORTH → (THEY, NORTH, AUTUMN) |

#### THEY × WEST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 00 01 10 |
| **Decimal** | 6 |
| **State** | (THEY, WEST, SUMMER) |
| **Name** | Growing Financial Institution |
| **Description** | Financial entity in rapid expansion. Growing assets under management, market share. |
| **Example** | Robinhood during growth phase, emerging exchange |
| **CES** | 65-80 |
| **SF** | 0.2-0.3 |
| **Risk** | Overextension, regulatory scrutiny |
| **Monetization** | Growing fee base, new products |
| **Typical trajectory** | T_AUTUMN → (THEY, WEST, AUTUMN) or T_SOUTH → (THEY, SOUTH, SUMMER) |

#### THEY × WEST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 00 01 11 |
| **Decimal** | 7 |
| **State** | (THEY, WEST, SPRING) |
| **Name** | New Financial Platform |
| **Description** | Newly launched financial exchange, investment platform, or fund. Experimenting with models. |
| **Example** | New cryptocurrency exchange, newly launched ETF |
| **CES** | 35-50 |
| **SF** | 0.3-0.5 |
| **Risk** | Failure to gain traction, regulatory issues |
| **Monetization** | Initial fees, seed investments |
| **Typical trajectory** | T_SUMMER → (THEY, WEST, SUMMER) or T_EAST → (THEY, EAST, SPRING) |

#### THEY × EAST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 00 10 00 |
| **Decimal** | 8 |
| **State** | (THEY, EAST, WINTER) |
| **Name** | Obsolete Technology Standard |
| **Description** | Once-dominant technology platform or standard now in decline. Being replaced. |
| **Example** | IBM mainframes (in decline), COBOL, Flash |
| **CES** | 15-30 |
| **SF** | 0.6-0.8 |
| **Risk** | Irrelevance, replacement |
| **Monetization** | Legacy support, maintenance fees |
| **Typical trajectory** | T_ME → (ME, EAST, WINTER) or T_SPRING → (THEY, EAST, SPRING) |

#### THEY × EAST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 00 10 01 |
| **Decimal** | 9 |
| **State** | (THEY, EAST, AUTUMN) |
| **Name** | Mature Technology Ecosystem |
| **Description** | Established technology platform in optimization phase. Maximizing revenue from existing technology. |
| **Example** | Microsoft (post-peak), Oracle, SAP |
| **CES** | 60-75 |
| **SF** | 0.2-0.4 |
| **Risk** | Disruption, failure to innovate |
| **Monetization** | Licensing, maintenance, enterprise contracts |
| **Typical trajectory** | T_WINTER → (THEY, EAST, WINTER) or T_SOUTH → (THEY, SOUTH, AUTUMN) |

#### THEY × EAST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 00 10 10 |
| **Decimal** | 10 |
| **State** | (THEY, EAST, SUMMER) |
| **Name** | Growing Technology Platform |
| **Description** | Technology platform experiencing network effects and rapid growth. Scaling user base. |
| **Example** | Facebook 2008-2012, Uber during growth phase |
| **CES** | 70-85 |
| **SF** | 0.1-0.3 |
| **Risk** | Scaling challenges, competition |
| **Monetization** | Platform fees, advertising, data |
| **Typical trajectory** | T_AUTUMN → (THEY, EAST, AUTUMN) or T_WEST → (THEY, WEST, SUMMER) |

#### THEY × EAST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 00 10 11 |
| **Decimal** | 11 |
| **State** | (THEY, EAST, SPRING) |
| **Name** | New Technology Platform |
| **Description** | Newly launched platform or ecosystem. Building network effects, seeking critical mass. |
| **Example** | Early Facebook (2004), early Twitter, new blockchain platform |
| **CES** | 40-55 |
| **SF** | 0.3-0.5 |
| **Risk** | Failure to achieve network effects |
| **Monetization** | Seed funding, early adopters |
| **Typical trajectory** | T_SUMMER → (THEY, EAST, SUMMER) or T_SOUTH → (THEY, SOUTH, SPRING) |

#### THEY × SOUTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 00 11 00 |
| **Decimal** | 12 |
| **State** | (THEY, SOUTH, WINTER) |
| **Name** | Dying Marketplace |
| **Description** | Once-dominant marketplace now in terminal decline. Losing buyers and sellers. |
| **Example** | Sears, Blockbuster, declining e-commerce platforms |
| **CES** | 10-25 |
| **SF** | 0.7-0.9 |
| **Risk** | Extinction |
| **Monetization** | Wind-down sales, asset liquidation |
| **Typical trajectory** | T_ME → (ME, SOUTH, WINTER) or T_SPRING → (THEY, SOUTH, SPRING) |

#### THEY × SOUTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 00 11 01 |
| **Decimal** | 13 |
| **State** | (THEY, SOUTH, AUTUMN) |
| **Name** | Mature Marketplace |
| **Description** | Established marketplace in optimization phase. Maximizing take rate, efficiency. |
| **Example** | eBay, Etsy, Amazon (marketplace segment) |
| **CES** | 65-80 |
| **SF** | 0.2-0.4 |
| **Risk** | Disintermediation, competition |
| **Monetization** | Commissions, listing fees, advertising |
| **Typical trajectory** | T_WINTER → (THEY, SOUTH, WINTER) or T_WEST → (THEY, WEST, AUTUMN) |

#### THEY × SOUTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 00 11 10 |
| **Decimal** | 14 |
| **State** | (THEY, SOUTH, SUMMER) |
| **Name** | Growing Marketplace |
| **Description** | Marketplace in rapid expansion. Adding buyers, sellers, categories. |
| **Example** | Amazon 2000s, Alibaba during growth |
| **CES** | 75-90 |
| **SF** | 0.1-0.2 |
| **Risk** | Operational scaling, quality control |
| **Monetization** | Growing commission base |
| **Typical trajectory** | T_AUTUMN → (THEY, SOUTH, AUTUMN) or T_EAST → (THEY, EAST, SUMMER) |

#### THEY × SOUTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 00 11 11 |
| **Decimal** | 15 |
| **State** | (THEY, SOUTH, SPRING) |
| **Name** | New Marketplace |
| **Description** | Newly launched marketplace platform. Building two-sided network. |
| **Example** | Early Etsy, early Airbnb |
| **CES** | 35-50 |
| **SF** | 0.3-0.5 |
| **Risk** | Chicken-and-egg problem |
| **Monetization** | Initial listings, seed funding |
| **Typical trajectory** | T_SUMMER → (THEY, SOUTH, SUMMER) or T_NORTH → (THEY, NORTH, SPRING) |

---

### 3.2. YOU States (A = 01)

#### YOU × NORTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 01 00 00 |
| **Decimal** | 16 |
| **State** | (YOU, NORTH, WINTER) |
| **Name** | Sanctioned Client |
| **Description** | Client or customer under regulatory sanctions or exclusion. Losing access. |
| **Example** | Company under trade sanctions, individual denied services |
| **CES** | 5-20 |
| **SF** | 0.7-0.9 |
| **Risk** | Complete exclusion |
| **Monetization** | None (seeking alternatives) |
| **Typical trajectory** | T_THEY → (THEY, NORTH, WINTER) or T_SPRING → (YOU, NORTH, SPRING) |

#### YOU × NORTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 01 00 01 |
| **Decimal** | 17 |
| **State** | (YOU, NORTH, AUTUMN) |
| **Name** | Government Client |
| **Description** | Client engaged with regulatory bodies in optimization phase. Regular compliance, stable relationship. |
| **Example** | Government contractor, regulated entity in compliance |
| **CES** | 45-60 |
| **SF** | 0.3-0.5 |
| **Risk** | Regulatory change, contract loss |
| **Monetization** | Government contracts, compliance spending |
| **Typical trajectory** | T_WINTER → (YOU, NORTH, WINTER) or T_WEST → (YOU, WEST, AUTUMN) |

#### YOU × NORTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 01 00 10 |
| **Decimal** | 18 |
| **State** | (YOU, NORTH, SUMMER) |
| **Name** | Client Lobbyist |
| **Description** | Client actively engaging with regulators to shape policy. Growing influence. |
| **Example** | Industry association member lobbying for favorable regulations |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Overreach, public backlash |
| **Monetization** | Influence-based returns |
| **Typical trajectory** | T_AUTUMN → (YOU, NORTH, AUTUMN) or T_SOUTH → (YOU, SOUTH, SUMMER) |

#### YOU × NORTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 01 00 11 |
| **Decimal** | 19 |
| **State** | (YOU, NORTH, SPRING) |
| **Name** | Citizen Activist |
| **Description** | Individual or group engaging with regulatory process for first time. Seeking change. |
| **Example** | Grassroots activist, public hearing participant |
| **CES** | 25-40 |
| **SF** | 0.4-0.6 |
| **Risk** | Irrelevance, being ignored |
| **Monetization** | Grants, donations |
| **Typical trajectory** | T_SUMMER → (YOU, NORTH, SUMMER) or T_EAST → (YOU, EAST, SPRING) |

#### YOU × WEST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 01 01 00 |
| **Decimal** | 20 |
| **State** | (YOU, WEST, WINTER) |
| **Name** | Defaulting Debtor |
| **Description** | Client unable to meet financial obligations. Bankruptcy, default. |
| **Example** | Bankrupt individual, defaulting borrower |
| **CES** | 0-15 |
| **SF** | 0.8-1.0 |
| **Risk** | Complete loss |
| **Monetization** | None (debt restructuring) |
| **Typical trajectory** | T_THEY → (THEY, WEST, WINTER) or T_SPRING → (YOU, WEST, SPRING) |

#### YOU × WEST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 01 01 01 |
| **Decimal** | 21 |
| **State** | (YOU, WEST, AUTUMN) |
| **Name** | Client-Partner |
| **Description** | Client engaged in mature financial relationship. Stable investments, regular returns. |
| **Example** | Long-term investor, joint venture partner |
| **CES** | 55-70 |
| **SF** | 0.2-0.4 |
| **Risk** | Market downturns, partner issues |
| **Monetization** | Dividends, profit share |
| **Typical trajectory** | T_WINTER → (YOU, WEST, WINTER) or T_NORTH → (YOU, NORTH, AUTUMN) |

#### YOU × WEST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 01 01 10 |
| **Decimal** | 22 |
| **State** | (YOU, WEST, SUMMER) |
| **Name** | Client-Investor |
| **Description** | Client actively investing and growing capital. Seeking returns, expanding portfolio. |
| **Example** | Active retail investor, angel investor |
| **CES** | 60-75 |
| **SF** | 0.2-0.3 |
| **Risk** | Market volatility, bad investments |
| **Monetization** | Investment returns |
| **Typical trajectory** | T_AUTUMN → (YOU, WEST, AUTUMN) or T_EAST → (YOU, EAST, SUMMER) |

#### YOU × WEST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 01 01 11 |
| **Decimal** | 23 |
| **State** | (YOU, WEST, SPRING) |
| **Name** | Crowd-Investor |
| **Description** | Client participating in early-stage funding. Backing new ventures. |
| **Example** | Kickstarter backer, early-stage angel |
| **CES** | 30-45 |
| **SF** | 0.3-0.5 |
| **Risk** | Loss of investment, project failure |
| **Monetization** | Early returns, perks |
| **Typical trajectory** | T_SUMMER → (YOU, WEST, SUMMER) or T_SOUTH → (YOU, SOUTH, SPRING) |

#### YOU × EAST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 01 10 00 |
| **Decimal** | 24 |
| **State** | (YOU, EAST, WINTER) |
| **Name** | Abandoning Client |
| **Description** | Client leaving a technology or platform. Switching away. |
| **Example** | User deleting account, company migrating off legacy system |
| **CES** | 10-25 |
| **SF** | 0.6-0.8 |
| **Risk** | Transition costs |
| **Monetization** | None (saving costs) |
| **Typical trajectory** | T_THEY → (THEY, EAST, WINTER) or T_SPRING → (YOU, EAST, SPRING) |

#### YOU × EAST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 01 10 01 |
| **Decimal** | 25 |
| **State** | (YOU, EAST, AUTUMN) |
| **Name** | Technology Expert |
| **Description** | Client with deep technology expertise. Consulting, advising on mature systems. |
| **Example** | Technology consultant, expert witness |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Obsolescence of expertise |
| **Monetization** | Consulting fees |
| **Typical trajectory** | T_WINTER → (YOU, EAST, WINTER) or T_WEST → (YOU, WEST, AUTUMN) |

#### YOU × EAST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 01 10 10 |
| **Decimal** | 26 |
| **State** | (YOU, EAST, SUMMER) |
| **Name** | Beta Tester |
| **Description** | Client testing new technology. Providing feedback, early adoption. |
| **Example** | Software beta tester, early adopter |
| **CES** | 40-55 |
| **SF** | 0.2-0.4 |
| **Risk** | Buggy products, wasted time |
| **Monetization** | Early access, discounts |
| **Typical trajectory** | T_AUTUMN → (YOU, EAST, AUTUMN) or T_SOUTH → (YOU, SOUTH, SUMMER) |

#### YOU × EAST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 01 10 11 |
| **Decimal** | 27 |
| **State** | (YOU, EAST, SPRING) |
| **Name** | Client-Researcher |
| **Description** | Client commissioning or guiding new technology development. Defining requirements. |
| **Example** | Client funding custom software, research sponsor |
| **CES** | 30-45 |
| **SF** | 0.3-0.5 |
| **Risk** | Project failure, misalignment |
| **Monetization** | Custom solutions |
| **Typical trajectory** | T_SUMMER → (YOU, EAST, SUMMER) or T_NORTH → (YOU, NORTH, SPRING) |

#### YOU × SOUTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 01 11 00 |
| **Decimal** | 28 |
| **State** | (YOU, SOUTH, WINTER) |
| **Name** | Lost Customer |
| **Description** | Client who has stopped buying. Churned, defected to competitor. |
| **Example** | Former loyal customer now using competitor |
| **CES** | 5-20 |
| **SF** | 0.7-0.9 |
| **Risk** | Permanent loss |
| **Monetization** | None |
| **Typical trajectory** | T_THEY → (THEY, SOUTH, WINTER) or T_SPRING → (YOU, SOUTH, SPRING) |

#### YOU × SOUTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 01 11 01 |
| **Decimal** | 29 |
| **State** | (YOU, SOUTH, AUTUMN) |
| **Name** | Client-Optimizer |
| **Description** | Mature client seeking better terms, discounts, efficiency. Maximizing value. |
| **Example** | Long-term customer negotiating bulk discount |
| **CES** | 45-60 |
| **SF** | 0.2-0.4 |
| **Risk** | Switching if terms not met |
| **Monetization** | Volume purchases |
| **Typical trajectory** | T_WINTER → (YOU, SOUTH, WINTER) or T_WEST → (YOU, WEST, AUTUMN) |

#### YOU × SOUTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 01 11 10 |
| **Decimal** | 30 |
| **State** | (YOU, SOUTH, SUMMER) |
| **Name** | Client-Ambassador |
| **Description** | Loyal, enthusiastic client referring others. Growing relationship. |
| **Example** | Brand advocate, referral source |
| **CES** | 55-70 |
| **SF** | 0.1-0.3 |
| **Risk** | Over-dependence on individual |
| **Monetization** | Repeat purchases, referrals |
| **Typical trajectory** | T_AUTUMN → (YOU, SOUTH, AUTUMN) or T_EAST → (YOU, EAST, SUMMER) |

#### YOU × SOUTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 01 11 11 |
| **Decimal** | 31 |
| **State** | (YOU, SOUTH, SPRING) |
| **Name** | First Customer |
| **Description** | Initial client for a new product or service. Validating market. |
| **Example** | First paying customer, pilot client |
| **CES** | 30-45 |
| **SF** | 0.3-0.5 |
| **Risk** | Product may not meet needs |
| **Monetization** | Initial revenue |
| **Typical trajectory** | T_SUMMER → (YOU, SOUTH, SUMMER) or T_NORTH → (YOU, NORTH, SPRING) |

---

### 3.3. ME States (A = 10)

#### ME × NORTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 10 00 00 |
| **Decimal** | 32 |
| **State** | (ME, NORTH, WINTER) |
| **Name** | Agency Liquidator |
| **Description** | Individual winding down regulatory or government operations. Ending programs. |
| **Example** | Liquidator of government agency, consultant for program termination |
| **CES** | 10-25 |
| **SF** | 0.7-0.9 |
| **Risk** | Personal liability, burnout |
| **Monetization** | Wind-down fees |
| **Typical trajectory** | T_WE → (WE, NORTH, WINTER) or T_SPRING → (ME, NORTH, SPRING) |

#### ME × NORTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 10 00 01 |
| **Decimal** | 33 |
| **State** | (ME, NORTH, AUTUMN) |
| **Name** | Regulatory Inspector |
| **Description** | Individual enforcing regulations, conducting audits. Stable, repetitive work. |
| **Example** | Tax auditor, safety inspector |
| **CES** | 45-60 |
| **SF** | 0.2-0.4 |
| **Risk** | Burnout, corruption risks |
| **Monetization** | Salary, fees |
| **Typical trajectory** | T_WINTER → (ME, NORTH, WINTER) or T_WEST → (ME, WEST, AUTUMN) |

#### ME × NORTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 10 00 10 |
| **Decimal** | 34 |
| **State** | (ME, NORTH, SUMMER) |
| **Name** | Professional Lobbyist |
| **Description** | Individual influencing regulations and policy. Growing influence, client base. |
| **Example** | K Street lobbyist, policy advocate |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Scandals, policy reversals |
| **Monetization** | Consulting fees |
| **Typical trajectory** | T_AUTUMN → (ME, NORTH, AUTUMN) or T_SOUTH → (ME, SOUTH, SUMMER) |

#### ME × NORTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 10 00 11 |
| **Decimal** | 35 |
| **State** | (ME, NORTH, SPRING) |
| **Name** | Grassroots Activist |
| **Description** | Individual starting to engage with regulatory process. Building awareness, seeking change. |
| **Example** | Community organizer, petition starter |
| **CES** | 25-40 |
| **SF** | 0.4-0.6 |
| **Risk** | Being ignored, lack of resources |
| **Monetization** | Donations, grants |
| **Typical trajectory** | T_SUMMER → (ME, NORTH, SUMMER) or T_EAST → (ME, EAST, SPRING) |

#### ME × WEST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 10 01 00 |
| **Decimal** | 36 |
| **State** | (ME, WEST, WINTER) |
| **Name** | Asset Liquidator |
| **Description** | Individual winding down investments, selling assets in decline. |
| **Example** | Bankruptcy trustee, liquidator |
| **CES** | 10-25 |
| **SF** | 0.7-0.9 |
| **Risk** | Personal financial loss |
| **Monetization** | Liquidation fees |
| **Typical trajectory** | T_WE → (WE, WEST, WINTER) or T_SPRING → (ME, WEST, SPRING) |

#### ME × WEST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 10 01 01 |
| **Decimal** | 37 |
| **State** | (ME, WEST, AUTUMN) |
| **Name** | Wealth Manager |
| **Description** | Individual managing mature investments. Optimizing returns, preserving capital. |
| **Example** | Financial advisor, portfolio manager |
| **CES** | 55-70 |
| **SF** | 0.2-0.4 |
| **Risk** | Market downturns, client loss |
| **Monetization** | Management fees |
| **Typical trajectory** | T_WINTER → (ME, WEST, WINTER) or T_NORTH → (ME, NORTH, AUTUMN) |

#### ME × WEST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 10 01 10 |
| **Decimal** | 38 |
| **State** | (ME, WEST, SUMMER) |
| **Name** | Active Investor |
| **Description** | Individual actively investing and growing capital. Seeking returns, scaling portfolio. |
| **Example** | Day trader, active angel investor |
| **CES** | 60-75 |
| **SF** | 0.2-0.3 |
| **Risk** | Market volatility, bad bets |
| **Monetization** | Investment returns |
| **Typical trajectory** | T_AUTUMN → (ME, WEST, AUTUMN) or T_EAST → (ME, EAST, SUMMER) |

#### ME × WEST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 10 01 11 |
| **Decimal** | 39 |
| **State** | (ME, WEST, SPRING) |
| **Name** | Angel Investor |
| **Description** | Individual beginning to invest in early-stage ventures. Seeking opportunities. |
| **Example** | First-time angel investor, crowdfunding participant |
| **CES** | 35-50 |
| **SF** | 0.3-0.5 |
| **Risk** | Loss of capital, inexperience |
| **Monetization** | Early-stage returns |
| **Typical trajectory** | T_SUMMER → (ME, WEST, SUMMER) or T_SOUTH → (ME, SOUTH, SPRING) |

#### ME × EAST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 10 10 00 |
| **Decimal** | 40 |
| **State** | (ME, EAST, WINTER) |
| **Name** | Tech Liquidator |
| **Description** | Individual winding down technology projects, shutting down failed ventures. |
| **Example** | Startup liquidator, project closer |
| **CES** | 10-25 |
| **SF** | 0.6-0.8 |
| **Risk** | Personal failure, financial loss |
| **Monetization** | Liquidation fees |
| **Typical trajectory** | T_WE → (WE, EAST, WINTER) or T_SPRING → (ME, EAST, SPRING) |

#### ME × EAST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 10 10 01 |
| **Decimal** | 41 |
| **State** | (ME, EAST, AUTUMN) |
| **Name** | Patent Attorney |
| **Description** | Individual managing intellectual property. Filing patents, protecting innovations. |
| **Example** | Patent lawyer, IP consultant |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Obsolescence, legal challenges |
| **Monetization** | Legal fees, royalties |
| **Typical trajectory** | T_WINTER → (ME, EAST, WINTER) or T_WEST → (ME, WEST, AUTUMN) |

#### ME × EAST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 10 10 10 |
| **Decimal** | 42 |
| **State** | (ME, EAST, SUMMER) |
| **Name** | Solo Inventor (Scaling) |
| **Description** | Individual scaling a technology venture. Growing without (or before) team. |
| **Example** | Solo founder with growing product, indie developer with hit app |
| **CES** | 55-70 |
| **SF** | 0.2-0.3 |
| **Risk** | Burnout, inability to scale alone |
| **Monetization** | Product sales, licensing |
| **Typical trajectory** | T_AUTUMN → (ME, EAST, AUTUMN) or T_WE → (WE, EAST, SUMMER) |

#### ME × EAST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 10 10 11 |
| **Decimal** | 43 |
| **State** | (ME, EAST, SPRING) |
| **Name** | Creator / Inventor |
| **Description** | Individual creating new technology, experimenting, ideating. The archetypal garage inventor. |
| **Example** | Steve Jobs in garage, solo developer prototyping |
| **CES** | 35-50 |
| **SF** | 0.2-0.4 |
| **Risk** | Failure to build, running out of resources |
| **Monetization** | Savings, grants, initial funding |
| **Typical trajectory** | T_SUMMER → (ME, EAST, SUMMER) or T_WE → (WE, EAST, SPRING) |

#### ME × SOUTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 10 11 00 |
| **Decimal** | 44 |
| **State** | (ME, SOUTH, WINTER) |
| **Name** | Bankruptcy Trustee |
| **Description** | Individual winding down market operations, liquidating businesses. |
| **Example** | Bankruptcy trustee, liquidator |
| **CES** | 10-25 |
| **SF** | 0.7-0.9 |
| **Risk** | Personal liability, emotional toll |
| **Monetization** | Trustee fees |
| **Typical trajectory** | T_WE → (WE, SOUTH, WINTER) or T_SPRING → (ME, SOUTH, SPRING) |

#### ME × SOUTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 10 11 01 |
| **Decimal** | 45 |
| **State** | (ME, SOUTH, AUTUMN) |
| **Name** | Sales Consultant |
| **Description** | Individual optimizing sales processes, consulting on market strategy. |
| **Example** | Sales coach, marketing consultant |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Market changes, client loss |
| **Monetization** | Consulting fees |
| **Typical trajectory** | T_WINTER → (ME, SOUTH, WINTER) or T_WEST → (ME, WEST, AUTUMN) |

#### ME × SOUTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 10 11 10 |
| **Decimal** | 46 |
| **State** | (ME, SOUTH, SUMMER) |
| **Name** | Top Salesperson |
| **Description** | Individual excelling in sales, building client base, growing revenue. |
| **Example** | Star sales rep, top real estate agent |
| **CES** | 60-75 |
| **SF** | 0.1-0.3 |
| **Risk** | Burnout, territory changes |
| **Monetization** | Commissions, bonuses |
| **Typical trajectory** | T_AUTUMN → (ME, SOUTH, AUTUMN) or T_WE → (WE, SOUTH, SUMMER) |

#### ME × SOUTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 10 11 11 |
| **Decimal** | 47 |
| **State** | (ME, SOUTH, SPRING) |
| **Name** | Market Pioneer |
| **Description** | Individual entering new market, finding first customers, establishing presence. |
| **Example** | First street vendor, pioneer in new territory |
| **CES** | 30-45 |
| **SF** | 0.3-0.5 |
| **Risk** | Market rejection, lack of demand |
| **Monetization** | First sales |
| **Typical trajectory** | T_SUMMER → (ME, SOUTH, SUMMER) or T_EAST → (ME, EAST, SPRING) |

---

### 3.4. WE States (A = 11)

#### WE × NORTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 11 00 00 |
| **Decimal** | 48 |
| **State** | (WE, NORTH, WINTER) |
| **Name** | Dissolution Committee |
| **Description** | Team winding down regulatory or government operations. Closing agencies, ending programs. |
| **Example** | Transition team for agency closure |
| **CES** | 15-30 |
| **SF** | 0.6-0.8 |
| **Risk** | Political challenges, incomplete closure |
| **Monetization** | Wind-down contracts |
| **Typical trajectory** | T_THEY → (THEY, NORTH, WINTER) or T_SPRING → (WE, NORTH, SPRING) |

#### WE × NORTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 11 00 01 |
| **Decimal** | 49 |
| **State** | (WE, NORTH, AUTUMN) |
| **Name** | Regulatory Commission |
| **Description** | Team running established regulatory body. Efficient enforcement, stable operations. |
| **Example** | Antimonopoly committee, utility commission |
| **CES** | 50-65 |
| **SF** | 0.2-0.4 |
| **Risk** | Capture, inefficiency |
| **Monetization** | Fees, fines |
| **Typical trajectory** | T_WINTER → (WE, NORTH, WINTER) or T_WEST → (WE, WEST, AUTUMN) |

#### WE × NORTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 11 00 10 |
| **Decimal** | 50 |
| **State** | (WE, NORTH, SUMMER) |
| **Name** | Trade Association |
| **Description** | Team building influence in regulatory domain. Expanding membership, growing power. |
| **Example** | Industry association, lobbying group |
| **CES** | 55-70 |
| **SF** | 0.2-0.3 |
| **Risk** | Overreach, public backlash |
| **Monetization** | Membership dues, lobbying fees |
| **Typical trajectory** | T_AUTUMN → (WE, NORTH, AUTUMN) or T_SOUTH → (WE, SOUTH, SUMMER) |

#### WE × NORTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 11 00 11 |
| **Decimal** | 51 |
| **State** | (WE, NORTH, SPRING) |
| **Name** | NGO / Activist Group |
| **Description** | Team forming to influence regulations or advocate for change. Building initial campaign. |
| **Example** | Newly formed non-profit, activist organization |
| **CES** | 30-45 |
| **SF** | 0.3-0.5 |
| **Risk** | Failure to gain traction |
| **Monetization** | Grants, donations |
| **Typical trajectory** | T_SUMMER → (WE, NORTH, SUMMER) or T_EAST → (WE, EAST, SPRING) |

#### WE × WEST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 11 01 00 |
| **Decimal** | 52 |
| **State** | (WE, WEST, WINTER) |
| **Name** | Liquidation Fund |
| **Description** | Team winding down investments, closing positions, returning capital. |
| **Example** | Fund in wind-down, liquidation team |
| **CES** | 10-25 |
| **SF** | 0.7-0.9 |
| **Risk** | Losses, investor lawsuits |
| **Monetization** | Liquidation fees |
| **Typical trajectory** | T_THEY → (THEY, WEST, WINTER) or T_SPRING → (WE, WEST, SPRING) |

#### WE × WEST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 11 01 01 |
| **Decimal** | 53 |
| **State** | (WE, WEST, AUTUMN) |
| **Name** | Private Equity |
| **Description** | Team managing mature investments. Harvesting returns, optimizing portfolio companies. |
| **Example** | Private equity firm, buyout fund |
| **CES** | 60-75 |
| **SF** | 0.2-0.4 |
| **Risk** | Economic downturns, bad acquisitions |
| **Monetization** | Carried interest, management fees |
| **Typical trajectory** | T_WINTER → (WE, WEST, WINTER) or T_NORTH → (WE, NORTH, AUTUMN) |

#### WE × WEST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 11 01 10 |
| **Decimal** | 54 |
| **State** | (WE, WEST, SUMMER) |
| **Name** | Hedge Fund / VC Fund |
| **Description** | Team actively investing and growing capital. Seeking returns, expanding portfolio. |
| **Example** | Venture capital firm, hedge fund |
| **CES** | 65-80 |
| **SF** | 0.1-0.3 |
| **Risk** | Market volatility, bad investments |
| **Monetization** | Management fees, carry |
| **Typical trajectory** | T_AUTUMN → (WE, WEST, AUTUMN) or T_EAST → (WE, EAST, SUMMER) |

#### WE × WEST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 11 01 11 |
| **Decimal** | 55 |
| **State** | (WE, WEST, SPRING) |
| **Name** | New Investment Fund |
| **Description** | Team forming new fund. Raising capital, defining strategy, seeking first investments. |
| **Example** | New VC fund raising first fund |
| **CES** | 35-50 |
| **SF** | 0.3-0.5 |
| **Risk** | Failure to raise, poor first investments |
| **Monetization** | Initial management fees |
| **Typical trajectory** | T_SUMMER → (WE, WEST, SUMMER) or T_SOUTH → (WE, SOUTH, SPRING) |

#### WE × EAST × WINTER
| Property | Value |
|----------|-------|
| **Code** | 11 10 00 |
| **Decimal** | 56 |
| **State** | (WE, EAST, WINTER) |
| **Name** | Tech Outsourcer |
| **Description** | Team maintaining legacy technology. Supporting declining systems, winding down. |
| **Example** | COBOL maintenance team, legacy system support |
| **CES** | 20-35 |
| **SF** | 0.5-0.7 |
| **Risk** | Obsolescence, skill irrelevance |
| **Monetization** | Maintenance contracts |
| **Typical trajectory** | T_THEY → (THEY, EAST, WINTER) or T_SPRING → (WE, EAST, SPRING) |

#### WE × EAST × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 11 10 01 |
| **Decimal** | 57 |
| **State** | (WE, EAST, AUTUMN) |
| **Name** | Tech Giant (Optimizing) |
| **Description** | Large technology company optimizing mature products. Maximizing revenue from existing tech. |
| **Example** | Microsoft (Windows division), Oracle |
| **CES** | 65-80 |
| **SF** | 0.2-0.3 |
| **Risk** | Disruption, missed innovation |
| **Monetization** | Licensing, enterprise sales |
| **Typical trajectory** | T_WINTER → (WE, EAST, WINTER) or T_WEST → (WE, WEST, AUTUMN) |

#### WE × EAST × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 11 10 10 |
| **Decimal** | 58 |
| **State** | (WE, EAST, SUMMER) |
| **Name** | Tech Startup (Scaling) |
| **Description** | Technology company in growth phase. Scaling product, team, and users. |
| **Example** | Series B/C startup, growing SaaS company |
| **CES** | 75-90 |
| **SF** | 0.1-0.2 |
| **Risk** | Scaling challenges, competition |
| **Monetization** | Subscriptions, licensing |
| **Typical trajectory** | T_AUTUMN → (WE, EAST, AUTUMN) or T_SOUTH → (WE, SOUTH, SUMMER) |

#### WE × EAST × SPRING
| Property | Value |
|----------|-------|
| **Code** | 11 10 11 |
| **Decimal** | 59 |
| **State** | (WE, EAST, SPRING) |
| **Name** | R&D Lab / Early Startup |
| **Description** | Team developing new technology. Experimenting, prototyping, seeking product-market fit. |
| **Example** | Early-stage startup, research lab |
| **CES** | 45-60 |
| **SF** | 0.2-0.4 |
| **Risk** | Technical failure, no market |
| **Monetization** | Grants, seed funding |
| **Typical trajectory** | T_SUMMER → (WE, EAST, SUMMER) or T_SOUTH → (WE, SOUTH, SPRING) |

#### WE × SOUTH × WINTER
| Property | Value |
|----------|-------|
| **Code** | 11 11 00 |
| **Decimal** | 60 |
| **State** | (WE, SOUTH, WINTER) |
| **Name** | Market Exit Team |
| **Description** | Team winding down market operations. Closing stores, exiting regions. |
| **Example** | Retail chain liquidation team |
| **CES** | 15-30 |
| **SF** | 0.6-0.8 |
| **Risk** | Losses, reputational damage |
| **Monetization** | Liquidation sales |
| **Typical trajectory** | T_THEY → (THEY, SOUTH, WINTER) or T_SPRING → (WE, SOUTH, SPRING) |

#### WE × SOUTH × AUTUMN
| Property | Value |
|----------|-------|
| **Code** | 11 11 01 |
| **Decimal** | 61 |
| **State** | (WE, SOUTH, AUTUMN) |
| **Name** | Consulting Firm |
| **Description** | Team optimizing market operations for clients. Mature, efficient, expertise-based. |
| **Example** | McKinsey, BCG, established consulting firm |
| **CES** | 60-75 |
| **SF** | 0.2-0.3 |
| **Risk** | Reputation dependence, competition |
| **Monetization** | Consulting fees |
| **Typical trajectory** | T_WINTER → (WE, SOUTH, WINTER) or T_WEST → (WE, WEST, AUTUMN) |

#### WE × SOUTH × SUMMER
| Property | Value |
|----------|-------|
| **Code** | 11 11 10 |
| **Decimal** | 62 |
| **State** | (WE, SOUTH, SUMMER) |
| **Name** | Scaling Enterprise |
| **Description** | Team rapidly expanding market presence. Opening new locations, acquiring customers. |
| **Example** | Franchise network, retail chain in growth |
| **CES** | 75-90 |
| **SF** | 0.1-0.2 |
| **Risk** | Overexpansion, quality control |
| **Monetization** | Sales, franchise fees |
| **Typical trajectory** | T_AUTUMN → (WE, SOUTH, AUTUMN) or T_EAST → (WE, EAST, SUMMER) |

#### WE × SOUTH × SPRING
| Property | Value |
|----------|-------|
| **Code** | 11 11 11 |
| **Decimal** | 63 |
| **State** | (WE, SOUTH, SPRING) |
| **Name** | Market Entrant |
| **Description** | Team entering new market. Finding first customers, establishing presence. |
| **Example** | Team launching in new geography |
| **CES** | 40-55 |
| **SF** | 0.2-0.4 |
| **Risk** | Market rejection |
| **Monetization** | Initial sales |
| **Typical trajectory** | T_SUMMER → (WE, SOUTH, SUMMER) or T_EAST → (WE, EAST, SPRING) |

---

## 4. Summary Statistics

| WHO | Count | CES Range (typical) | SF Range (typical) |
|-----|-------|---------------------|--------------------|
| **THEY (00)** | 16 | 0-85 | 0.1-1.0 |
| **YOU (01)** | 16 | 0-75 | 0.1-1.0 |
| **ME (10)** | 16 | 0-75 | 0.1-0.9 |
| **WE (11)** | 16 | 10-90 | 0.1-0.9 |

| WHERE | Count | CES Range (typical) |
|-------|-------|---------------------|
| **EAST (10)** | 16 | 10-90 |
| **SOUTH (11)** | 16 | 5-93 |
| **WEST (01)** | 16 | 0-80 |
| **NORTH (00)** | 16 | 0-70 |

| WHEN | Count | CES Range (typical) |
|------|-------|---------------------|
| **SPRING (10)** | 16 | 25-60 |
| **SUMMER (11)** | 16 | 55-93 |
| **AUTUMN (01)** | 16 | 45-80 |
| **WINTER (00)** | 16 | 0-30 |

---

## 5. Quick Reference Card

| Code | WHO | WHERE | WHEN |
|------|-----|-------|------|
| `10` | ME | EAST | SPRING |
| `11` | WE | SOUTH | SUMMER |
| `01` | YOU | WEST | AUTUMN |
| `00` | THEY | NORTH | WINTER |

**Memory Rule:**
- `10` = beginning (ME, EAST, SPRING)
- `11` = peak (WE, SOUTH, SUMMER)
- `01` = maturity (YOU, WEST, AUTUMN)
- `00` = end (THEY, NORTH, WINTER)

---

*This document provides the complete catalog of all 64 states in Economic Geometry, serving as the definitive reference for state identification and classification.*
