# GEODESICS: Optimal Transformation Paths in Ω

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 4, Section 4.2

---

## 1. Introduction to Geodesics

In the economic state space Ω, a **geodesic** represents the shortest path between two business configurations. Just as a geodesic on Earth's surface is the shortest route between two points, a geodesic in Ω is the most efficient sequence of transformations from one business state to another.

**Definition 1.1 (Geodesic).** A geodesic between states ω₁ and ω₂ is a sequence of states γ = (γ₀, γ₁, ..., γₖ) such that:
1. γ₀ = ω₁ (starting state)
2. γₖ = ω₂ (target state)
3. For each consecutive pair, d(γᵢ, γᵢ₊₁) = 1 (each step changes exactly one bit)
4. k = d(ω₁, ω₂) (the sequence has minimum possible length)

---

## 2. Properties of Geodesics

### 2.1. Length and Minimality

**Theorem 2.1 (Geodesic Length).** The length of any geodesic between ω₁ and ω₂ equals their Hamming distance d(ω₁, ω₂).

*Proof.* By definition, each step changes exactly one bit. To go from ω₁ to ω₂, we must change all bits where they differ. The minimum number of steps required is exactly the number of differing bits, which is d(ω₁, ω₂). Any path with fewer steps would leave some differences unchanged.

### 2.2. Bit Independence

Along a geodesic, bits are changed independently and in some order. The order can be any permutation of the positions that differ.

**Theorem 2.2 (Number of Geodesics).** The number of distinct geodesics between ω₁ and ω₂ is:

```
N(ω₁, ω₂) = d! / (n₀! n₁! n₂! n₃! n₄! n₅! n₆!)
```

where d = d(ω₁, ω₂) and nⱼ is the number of bit positions that require change from 0→1 (if ω₁ has 0 and ω₂ has 1) or 1→0 (if ω₁ has 1 and ω₂ has 0), grouped by type.

**Simpler form:** If the d differing bits are all independent (no special constraints), then:

```
N(ω₁, ω₂) = d!
```

This is because we can choose any order to change the d bits, and each order gives a different path.

**Example 2.1.** For d = 3 with all bits independent, there are 3! = 6 distinct geodesics.

### 2.3. Geometric Interpretation

In the 6-dimensional hypercube {0,1}⁶:
- Each state is a vertex
- Each edge connects vertices differing in exactly one bit
- A geodesic is a path along edges that never backtracks and has minimum length
- Geodesics correspond to monotonic paths in the hypercube

---

## 3. Examples of Geodesics

### 3.1. Simple Case: d = 1

When d = 1, there is exactly one geodesic (the single edge).

**Example 3.1.** ω₁ = (ME, EAST, SPRING) = 10 10 10
ω₂ = (ME, EAST, SUMMER) = 10 10 11

d = 1 (only bit 6 differs)
Geodesic: [10 10 10 → 10 10 11]

### 3.2. d = 2 Case

**Example 3.2.** ω₁ = (ME, EAST, SPRING) = 10 10 10
ω₂ = (WE, EAST, SPRING) = 11 10 10

d = 1? Wait — check:
- Bit 1: 1 vs 1? ME=10, WE=11 → bit1: 1 vs 1 (same)
- Bit 2: 0 vs 1 (differs)
Actually, let's calculate properly:

ME = 10, WE = 11:
- Bit 1: 1 vs 1 (same)
- Bit 2: 0 vs 1 (differs)
So only bit 2 differs → d = 1

Let's choose a true d=2 example:

ω₁ = (ME, EAST, SPRING) = 10 10 10
ω₂ = (WE, SOUTH, SPRING) = 11 11 10

Differences:
- Bit 2: 0→1 (agency second bit)
- Bit 4: 0→1 (vector second bit)
d = 2

Geodesics (2! = 2 paths):

Path 1 (change agency first):
10 10 10 → 11 10 10 (change bit 2) → 11 11 10 (change bit 4)

Path 2 (change vector first):
10 10 10 → 10 11 10 (change bit 4) → 11 11 10 (change bit 2)

### 3.3. d = 3 Case — Complete Example

**Example 3.3.** ω₁ = (ME, EAST, SPRING) = 10 10 10
ω₂ = (WE, SOUTH, SUMMER) = 11 11 11

Differences:
- Bit 2: 0→1 (agency: ME→WE)
- Bit 4: 0→1 (vector: EAST→SOUTH)
- Bit 6: 0→1 (phase: SPRING→SUMMER)
d = 3

Number of geodesics = 3! = 6

**All 6 geodesics:**

1. Agency → Vector → Phase:
   10 10 10 → 11 10 10 → 11 11 10 → 11 11 11

2. Agency → Phase → Vector:
   10 10 10 → 11 10 10 → 11 10 11 → 11 11 11

3. Vector → Agency → Phase:
   10 10 10 → 10 11 10 → 11 11 10 → 11 11 11

4. Vector → Phase → Agency:
   10 10 10 → 10 11 10 → 10 11 11 → 11 11 11

5. Phase → Agency → Vector:
   10 10 10 → 10 10 11 → 11 10 11 → 11 11 11

6. Phase → Vector → Agency:
   10 10 10 → 10 10 11 → 10 11 11 → 11 11 11

### 3.4. Business Interpretation of Different Paths

Each geodesic represents a different strategic sequence:

| Path | Sequence | Business Meaning |
|------|----------|------------------|
| 1 | Agency → Vector → Phase | First build team, then enter market, then grow |
| 2 | Agency → Phase → Vector | First build team, then grow, then enter market |
| 3 | Vector → Agency → Phase | First enter market, then build team, then grow |
| 4 | Vector → Phase → Agency | First enter market, then grow, then build team |
| 5 | Phase → Agency → Vector | First grow, then build team, then enter market |
| 6 | Phase → Vector → Agency | First grow, then enter market, then build team |

Each sequence has different practical implications and risks.

---

## 4. Geodesics with Mixed Bit Changes

### 4.1. When Bits Change in Different Directions

Not all bit changes are 0→1; some may be 1→0.

**Example 4.1.** ω₁ = (WE, SOUTH, SUMMER) = 11 11 11
ω₂ = (ME, NORTH, WINTER) = 10 00 00

Differences:
- Bit 1: 1→1? WE=11, ME=10 → bit1: 1 vs 1 (same)
- Bit 2: 1→0 (WE→ME)
- Bit 3: 1→0 (SOUTH→NORTH)
- Bit 4: 1→0 (SOUTH second bit)
- Bit 5: 1→0 (SUMMER→WINTER)
- Bit 6: 1→0 (SUMMER second bit)

Actually, let's calculate systematically:

WE=11, ME=10:
- Bit1: 1 vs 1 (same)
- Bit2: 1 vs 0 (differs)

SOUTH=11, NORTH=00:
- Bit3: 1 vs 0 (differs)
- Bit4: 1 vs 0 (differs)

SUMMER=11, WINTER=00:
- Bit5: 1 vs 0 (differs)
- Bit6: 1 vs 0 (differs)

Total differences: bits 2,3,4,5,6 → d = 5

Number of geodesics = 5! = 120 possible paths

### 4.2. Symmetric Properties

**Theorem 4.1 (Reversibility).** If γ = (γ₀, γ₁, ..., γₖ) is a geodesic from ω₁ to ω₂, then its reverse γ' = (γₖ, γₖ₋₁, ..., γ₀) is a geodesic from ω₂ to ω₁.

*Proof.* Reversing preserves the property that consecutive states differ in exactly one bit, and the length remains k = d(ω₁, ω₂) = d(ω₂, ω₁).

---

## 5. Geodesics and Strategic Planning

### 5.1. Choosing Among Geodesics

When multiple geodesics exist, the choice depends on:

1. **Resource constraints** — some changes may be easier/cheaper first
2. **Market timing** — certain sequences may align better with external conditions
3. **Risk tolerance** — different sequences expose the business to different risks
4. **Path friction** — some intermediate states may have high SF

### 5.2. Friction Along Geodesics

**Definition 5.1 (Path Friction).** For a geodesic γ = (γ₀, γ₁, ..., γₖ), the path friction is:

```
SF(γ) = (1/(k+1)) ∑_{i=0}^{k} SF(γᵢ)
```

or alternatively, the maximum friction along the path:

```
SF_max(γ) = max_{i} SF(γᵢ)
```

**Optimal geodesic** minimizes either average or maximum friction.

**Example 5.1.** For the 6 geodesics in Example 3.3, suppose:

| State | SF |
|-------|-----|
| 10 10 10 | 0.2 |
| 11 10 10 | 0.18 |
| 10 11 10 | 0.25 |
| 10 10 11 | 0.3 |
| 11 11 10 | 0.15 |
| 11 10 11 | 0.22 |
| 10 11 11 | 0.35 |
| 11 11 11 | 0.1 |

Path frictions:
- Path 1: (0.2, 0.18, 0.15, 0.1) → avg = 0.1575, max = 0.2
- Path 2: (0.2, 0.18, 0.22, 0.1) → avg = 0.175, max = 0.22
- Path 3: (0.2, 0.25, 0.15, 0.1) → avg = 0.175, max = 0.25
- Path 4: (0.2, 0.25, 0.35, 0.1) → avg = 0.225, max = 0.35
- Path 5: (0.2, 0.3, 0.22, 0.1) → avg = 0.205, max = 0.3
- Path 6: (0.2, 0.3, 0.35, 0.1) → avg = 0.2375, max = 0.35

**Optimal choice:** Path 1 (Agency → Vector → Phase) minimizes both average and maximum friction.

---

## 6. Geodesics and Transformation Operators

### 6.1. Relation to Basic Operators

Each step in a geodesic corresponds to applying one of the 12 basic transformation operators:
- T_ME, T_WE, T_YOU, T_THEY (agency changes)
- T_EAST, T_SOUTH, T_WEST, T_NORTH (vector changes)
- T_SPRING, T_SUMMER, T_AUTUMN, T_WINTER (phase changes)

**Example 6.1.** Path 1 from Example 3.3:
- Step 1: 10 10 10 → 11 10 10 = T_WE
- Step 2: 11 10 10 → 11 11 10 = T_SOUTH
- Step 3: 11 11 10 → 11 11 11 = T_SUMMER

### 6.2. Composite Operators

A geodesic corresponds to a composite operator:

```
T_composite = Tₖ ∘ Tₖ₋₁ ∘ ... ∘ T₁
```

where the composition order is right-to-left (first apply T₁, then T₂, etc.).

**Example 6.2.** For Path 1:
T_composite = T_SUMMER ∘ T_SOUTH ∘ T_WE

This means: first change agency to WE, then change vector to SOUTH, then change phase to SUMMER.

---

## 7. Beyond Geodesics: Non-Minimal Paths

### 7.1. When Longer Paths Are Better

Sometimes the shortest path (geodesic) is not the best path because:
- Intermediate states may have prohibitively high SF
- External conditions may favor certain sequences
- Learning and adaptation may require intermediate steps

### 7.2. Quasi-Geodesics

**Definition 7.1 (Quasi-Geodesic).** A path γ = (γ₀, γ₁, ..., γₘ) from ω₁ to ω₂ is a quasi-geodesic if:
1. γ₀ = ω₁, γₘ = ω₂
2. d(γᵢ, γᵢ₊₁) = 1 for all i
3. m > d(ω₁, ω₂) (longer than minimum)

Quasi-geodesics allow "detours" through intermediate states that may be more desirable.

---

## 8. Summary

| Concept | Definition | Business Meaning |
|---------|------------|------------------|
| **Geodesic** | Minimum-length path between states | Most efficient transformation sequence |
| **Geodesic length** | d(ω₁, ω₂) | Number of fundamental changes needed |
| **Number of geodesics** | d! (for independent bits) | Number of possible strategic sequences |
| **Path friction** | Average or max SF along path | Difficulty/smoothness of transition |
| **Optimal geodesic** | Minimizes path friction | Best sequence given current constraints |

**Key Insight:** Geodesics provide the mathematically optimal paths between business configurations, but practical considerations (friction, resources, timing) may lead to choosing among the many possible geodesics or even taking longer quasi-geodesic paths.

---

*This document establishes the theory of geodesics in Economic Geometry, providing the foundation for strategic path planning and transformation sequence optimization.*
