# SPACE DEFINITION: Ω = A × V × T

## Foundational Axioms of Economic Geometry

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 2, Sections 2.1-2.2

---

## 1. The Fundamental Theorem

**Theorem (Structure of Economic Reality).** Every economic entity can be uniquely represented as a vector **ω** in the product space:

```
Ω = A × V × T
```

where:
- **A** (WHO — Agency Layer): The subject of economic action
- **V** (WHERE — Vector Layer): The direction of capital accumulation
- **T** (WHEN — Phase Layer): The structural time phase

**Cardinality:** |Ω| = |A| × |V| × |T| = 4 × 4 × 4 = **64 canonical states**

---

## 2. The Agency Layer (A — WHO)

**Definition.** A is the set of fundamental types of economic subjects, answering the question "who captures value?"

| Element | Code | Name | Structural Meaning |
|---------|------|------|-------------------|
| **ME** | `10` | Individual | Solo founder, sole proprietor, individual agent |
| **WE** | `11` | Team | Collective agent, partnership, organized group |
| **YOU** | `01` | Client | Other-directed agent, value defined by recipient |
| **THEY** | `00` | System | Platform, institution, market as subject |

**Binary Structure:**
- First bit (`1`/`0`): individual (ME, YOU) vs. collective (WE, THEY)
- Second bit (`0`/`1`): active/external (ME, WE) vs. passive/internal (YOU, THEY)

**Axiom A1 (Completeness).** These four types exhaust all possible modes of economic agency. Any economic subject can be classified into exactly one of these categories.

**Axiom A2 (Orthogonality).** Agency type is independent of vector and phase dimensions.

---

## 3. The Vector Layer (V — WHERE)

**Definition.** V is the set of fundamental directions of value accumulation, answering the question "where does value flow?"

| Element | Code | Name | Structural Meaning |
|---------|------|------|-------------------|
| **EAST** | `10` | Innovation | Technology, new knowledge, R&D, patents |
| **SOUTH** | `11` | Market | Distribution, access, customers, scale |
| **WEST** | `01` | Capital | Ownership, finance, control, assets |
| **NORTH** | `00` | Authority | Regulation, standards, power, compliance |

**Binary Structure:**
- First bit (`1`/`0`): future/new (EAST, WEST) vs. past/old (SOUTH, NORTH)
- Second bit (`0`/`1`): material/tangible (EAST, SOUTH) vs. immaterial/intangible (WEST, NORTH)

**Axiom V1 (Completeness).** These four vectors exhaust all possible directions of capital accumulation. Any economic flow can be mapped to exactly one of these categories.

**Axiom V2 (Orthogonality).** Vector direction is independent of agency and phase dimensions.

---

## 4. The Phase Layer (T — WHEN)

**Definition.** T is the set of fundamental structural phases, answering the question "at what stage of the lifecycle?"

| Element | Code | Name | Structural Meaning |
|---------|------|------|-------------------|
| **SPRING** | `10` | Creation | Experimentation, inception, MVP, uncertainty |
| **SUMMER** | `11` | Growth | Scaling, expansion, rapid development |
| **AUTUMN** | `01` | Optimization | Maturity, extraction, efficiency, harvesting |
| **WINTER** | `00` | Decline | Transformation, decay, crisis, renewal |

**Binary Structure:**
- First bit (`1`/`0`): growth (SPRING, SUMMER) vs. decline (AUTUMN, WINTER)
- Second bit (`0`/`1`): becoming/process (SPRING, AUTUMN) vs. structure/result (SUMMER, WINTER)

**Axiom T1 (Completeness).** These four phases exhaust all possible structural time states. Any economic process at any moment can be assigned to exactly one phase.

**Axiom T2 (Orthogonality).** Phase is independent of agency and vector dimensions.

---

## 5. The Product Space Ω

**Definition 5.1.** The full economic state space Ω is the Cartesian product:

```
Ω = A × V × T = { (a, v, t) | a ∈ A, v ∈ V, t ∈ T }
```

**Definition 5.2 (Canonical Encoding).** There exists a bijective mapping Φ: Ω → {0,1}⁶ given by:

```
Φ(a, v, t) = (code(a) || code(v) || code(t))
```

where `||` denotes concatenation, and codes are as defined above.

**Example 5.1.** ω = (WE, EAST, SUMMER) → Φ(ω) = `11 10 11` = 111011₂ = 59₁₀

**Example 5.2.** ω = (THEY, NORTH, WINTER) → Φ(ω) = `00 00 00` = 000000₂ = 0₁₀

---

## 6. Visualization of the Space

**6.1. 3D Cube Representation**

The space Ω can be visualized as a 4×4×4 cube, where:
- X-axis: Agency (A) — 4 positions: ME, WE, YOU, THEY
- Y-axis: Vector (V) — 4 positions: EAST, SOUTH, WEST, NORTH
- Z-axis: Phase (T) — 4 positions: SPRING, SUMMER, AUTUMN, WINTER

Each cell (a, v, t) contains a unique business configuration.

**6.2. Coordinate System**

```
Position (a, v, t) where:
a ∈ {ME(10), WE(11), YOU(01), THEY(00)}
v ∈ {EAST(10), SOUTH(11), WEST(01), NORTH(00)}
t ∈ {SPRING(10), SUMMER(11), AUTUMN(01), WINTER(00)}
```

**6.3. Notable Regions**

| Region | Description | Coordinates |
|--------|-------------|-------------|
| **Innovation Zone** | Creation of new technology | {ME,WE} × EAST × {SPRING,SUMMER} |
| **Market Power Zone** | Dominant market positions | {WE,THEY} × SOUTH × {SUMMER,AUTUMN} |
| **Financial Zone** | Capital concentration | {ME,WE,THEY} × WEST × {SUMMER,AUTUMN} |
| **Regulatory Zone** | Authority and compliance | {THEY,WE} × NORTH × {AUTUMN,WINTER} |
| **Crisis Zone** | Structural instability | {ME,YOU} × NORTH × WINTER |
| **Birth Zone** | New ventures | {ME,WE} × EAST × SPRING |
| **Death Zone** | Terminal states | ANY × ANY × WINTER |

---

## 7. Formal Properties

**Theorem 7.1 (Dimensionality).** Ω is exactly 3-dimensional. No additional independent dimensions are necessary for complete structural description of economic configurations at this level of abstraction.

*Proof sketch.* The three dimensions (agency, vector, phase) correspond to the fundamental questions of economic action: subject, direction, and temporal modality. Any economic phenomenon can be fully described by answering these three questions.

**Theorem 7.2 (Discreteness).** Ω is a discrete space with exactly 64 points. This discreteness is not an approximation but a structural feature — economic reality at the configurational level is inherently discrete.

*Proof.* By construction from finite sets A, V, T.

**Theorem 7.3 (Completeness).** Every possible economic configuration (at the structural level of analysis) corresponds to exactly one point in Ω.

*Proof.* For any business, one can determine: Who is the primary agent? (ME/WE/YOU/THEY); Where is value primarily accumulating? (EAST/SOUTH/WEST/NORTH); What phase is the business in? (SPRING/SUMMER/AUTUMN/WINTER). This triple uniquely identifies the state.

**Theorem 7.4 (Orthogonality).** The dimensions A, V, T are mutually independent: fixing values in two dimensions does not constrain the possible values in the third.

*Proof.* Exhibiting examples: (ME, NORTH, WINTER) — individual lobbyist in declining regulations; (THEY, EAST, SPRING) — platform creating new market; (WE, WEST, AUTUMN) — team optimizing mature capital; (YOU, SOUTH, SUMMER) — client service in growing market. All combinations are empirically possible.

---

## 8. Philosophical Interpretation

**8.1. The Three Questions**

Every economic configuration answers three fundamental questions:

1. **WHO?** — The subject question: who acts, who decides, who owns?
2. **WHERE?** — The direction question: where does value flow, what is accumulated?
3. **WHEN?** — The time question: at what stage, in what phase?

**8.2. Invariance**

The space Ω is invariant under:
- Renaming of specific businesses (structural types remain)
- Rescaling of quantitative measures (qualitative structure persists)
- Changes in external context (the structural possibilities are universal)

**8.3. Reality Status**

The states in Ω are not mere classifications but **structural attractors** — configurations toward which real businesses tend to crystallize. They represent the fundamental morphological types of economic organization.

---

## 9. Relation to Other Frameworks

| Framework | Correspondence |
|-----------|----------------|
| **SUBIT-64** | Direct implementation: Ω = SUBIT space |
| **Business Model Canvas** | Each BMC configuration maps to a region in Ω |
| **Porter's Generic Strategies** | Map to specific subspaces of V-dimension |
| **Product Lifecycle** | Maps to T-dimension trajectory |
| **Organizational Structures** | Map to A-dimension configurations |

---

## 10. Summary Table

| Dimension | Elements | Codes | Binary Structure |
|-----------|----------|-------|------------------|
| **A (WHO)** | ME, WE, YOU, THEY | 10, 11, 01, 00 | [individual/collective] × [active/passive] |
| **V (WHERE)** | EAST, SOUTH, WEST, NORTH | 10, 11, 01, 00 | [future/past] × [material/immaterial] |
| **T (WHEN)** | SPRING, SUMMER, AUTUMN, WINTER | 10, 11, 01, 00 | [growth/decline] × [becoming/structure] |

**Space Ω:** 4 × 4 × 4 = **64 canonical states**

**Encoding:** 2 + 2 + 2 = **6 bits** → {0,1}⁶

**Range:** 000000₂ (0₁₀) to 111111₂ (63₁₀)

---

*This document establishes the foundational space definition for Economic Geometry. All further developments — metric, operators, observables — build upon this axiomatic basis.*
