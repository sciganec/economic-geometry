# STRUCTURAL FRICTION TENSOR: SF Values Across Ω

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 4, Section 4.3; Appendix Reference

---

## 1. Introduction to the Structural Friction Tensor

**Structural Friction (SF)** measures the internal inconsistency of a business configuration — the degree of tension or misalignment between its agency, vector, and phase dimensions. Unlike CES, which measures overall viability, SF specifically captures structural coherence.

**Definition Reminder:**
```
SF(ω) = (α·Δ_agency + β·Δ_vector + γ·Δ_phase + δ·Δ_pairwise) / (α+β+γ+δ)
```

where Δ_agency, Δ_vector, Δ_phase are self-consistency measures, and Δ_pairwise captures cross-dimensional mismatches.

---

## 2. SF Value Tables by Agency

### 2.1. SF for THEY States (A = 00)

| Phase → Vector ↓ | WINTER (00) | AUTUMN (01) | SUMMER (11) | SPRING (10) |
|------------------|-------------|-------------|-------------|-------------|
| **NORTH (00)** | 0.8-1.0 | 0.3-0.5 | 0.2-0.4 | 0.3-0.5 |
| **WEST (01)** | 0.8-1.0 | 0.2-0.4 | 0.2-0.3 | 0.3-0.5 |
| **EAST (10)** | 0.6-0.8 | 0.2-0.4 | 0.1-0.3 | 0.3-0.5 |
| **SOUTH (11)** | 0.7-0.9 | 0.2-0.4 | 0.1-0.2 | 0.3-0.5 |

**Detailed THEY SF Table:**

| State | Code | SF Range | Typical SF | SF Level |
|-------|------|----------|------------|----------|
| (THEY, NORTH, WINTER) | 00 00 00 | 0.8-1.0 | 0.90 | 🔴 Critical |
| (THEY, NORTH, AUTUMN) | 00 00 01 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (THEY, NORTH, SUMMER) | 00 00 10 | 0.2-0.4 | 0.30 | 🟢 Low |
| (THEY, NORTH, SPRING) | 00 00 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (THEY, WEST, WINTER) | 00 01 00 | 0.8-1.0 | 0.90 | 🔴 Critical |
| (THEY, WEST, AUTUMN) | 00 01 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (THEY, WEST, SUMMER) | 00 01 10 | 0.2-0.3 | 0.25 | 🟢 Low |
| (THEY, WEST, SPRING) | 00 01 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (THEY, EAST, WINTER) | 00 10 00 | 0.6-0.8 | 0.70 | 🟠 High |
| (THEY, EAST, AUTUMN) | 00 10 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (THEY, EAST, SUMMER) | 00 10 10 | 0.1-0.3 | 0.20 | 🟢 Very Low |
| (THEY, EAST, SPRING) | 00 10 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (THEY, SOUTH, WINTER) | 00 11 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (THEY, SOUTH, AUTUMN) | 00 11 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (THEY, SOUTH, SUMMER) | 00 11 10 | 0.1-0.2 | 0.15 | 🟢 Very Low |
| (THEY, SOUTH, SPRING) | 00 11 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |

---

### 2.2. SF for YOU States (A = 01)

| Phase → Vector ↓ | WINTER (00) | AUTUMN (01) | SUMMER (11) | SPRING (10) |
|------------------|-------------|-------------|-------------|-------------|
| **NORTH (00)** | 0.7-0.9 | 0.3-0.5 | 0.2-0.4 | 0.4-0.6 |
| **WEST (01)** | 0.8-1.0 | 0.2-0.4 | 0.2-0.3 | 0.3-0.5 |
| **EAST (10)** | 0.6-0.8 | 0.2-0.4 | 0.2-0.4 | 0.3-0.5 |
| **SOUTH (11)** | 0.7-0.9 | 0.2-0.4 | 0.1-0.3 | 0.3-0.5 |

**Detailed YOU SF Table:**

| State | Code | SF Range | Typical SF | SF Level |
|-------|------|----------|------------|----------|
| (YOU, NORTH, WINTER) | 01 00 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (YOU, NORTH, AUTUMN) | 01 00 01 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (YOU, NORTH, SUMMER) | 01 00 10 | 0.2-0.4 | 0.30 | 🟢 Low |
| (YOU, NORTH, SPRING) | 01 00 11 | 0.4-0.6 | 0.50 | 🟡 Moderate |
| (YOU, WEST, WINTER) | 01 01 00 | 0.8-1.0 | 0.90 | 🔴 Critical |
| (YOU, WEST, AUTUMN) | 01 01 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (YOU, WEST, SUMMER) | 01 01 10 | 0.2-0.3 | 0.25 | 🟢 Low |
| (YOU, WEST, SPRING) | 01 01 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (YOU, EAST, WINTER) | 01 10 00 | 0.6-0.8 | 0.70 | 🟠 High |
| (YOU, EAST, AUTUMN) | 01 10 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (YOU, EAST, SUMMER) | 01 10 10 | 0.2-0.4 | 0.30 | 🟢 Low |
| (YOU, EAST, SPRING) | 01 10 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (YOU, SOUTH, WINTER) | 01 11 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (YOU, SOUTH, AUTUMN) | 01 11 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (YOU, SOUTH, SUMMER) | 01 11 10 | 0.1-0.3 | 0.20 | 🟢 Very Low |
| (YOU, SOUTH, SPRING) | 01 11 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |

---

### 2.3. SF for ME States (A = 10)

| Phase → Vector ↓ | WINTER (00) | AUTUMN (01) | SUMMER (11) | SPRING (10) |
|------------------|-------------|-------------|-------------|-------------|
| **NORTH (00)** | 0.7-0.9 | 0.2-0.4 | 0.2-0.4 | 0.4-0.6 |
| **WEST (01)** | 0.7-0.9 | 0.2-0.4 | 0.2-0.3 | 0.3-0.5 |
| **EAST (10)** | 0.6-0.8 | 0.2-0.4 | 0.2-0.3 | 0.2-0.4 |
| **SOUTH (11)** | 0.7-0.9 | 0.2-0.4 | 0.1-0.3 | 0.3-0.5 |

**Detailed ME SF Table:**

| State | Code | SF Range | Typical SF | SF Level |
|-------|------|----------|------------|----------|
| (ME, NORTH, WINTER) | 10 00 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (ME, NORTH, AUTUMN) | 10 00 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, NORTH, SUMMER) | 10 00 10 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, NORTH, SPRING) | 10 00 11 | 0.4-0.6 | 0.50 | 🟡 Moderate |
| (ME, WEST, WINTER) | 10 01 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (ME, WEST, AUTUMN) | 10 01 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, WEST, SUMMER) | 10 01 10 | 0.2-0.3 | 0.25 | 🟢 Low |
| (ME, WEST, SPRING) | 10 01 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (ME, EAST, WINTER) | 10 10 00 | 0.6-0.8 | 0.70 | 🟠 High |
| (ME, EAST, AUTUMN) | 10 10 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, EAST, SUMMER) | 10 10 10 | 0.2-0.3 | 0.25 | 🟢 Low |
| (ME, EAST, SPRING) | 10 10 11 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, SOUTH, WINTER) | 10 11 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (ME, SOUTH, AUTUMN) | 10 11 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (ME, SOUTH, SUMMER) | 10 11 10 | 0.1-0.3 | 0.20 | 🟢 Very Low |
| (ME, SOUTH, SPRING) | 10 11 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |

---

### 2.4. SF for WE States (A = 11)

| Phase → Vector ↓ | WINTER (00) | AUTUMN (01) | SUMMER (11) | SPRING (10) |
|------------------|-------------|-------------|-------------|-------------|
| **NORTH (00)** | 0.6-0.8 | 0.2-0.4 | 0.2-0.3 | 0.3-0.5 |
| **WEST (01)** | 0.7-0.9 | 0.2-0.4 | 0.1-0.3 | 0.3-0.5 |
| **EAST (10)** | 0.5-0.7 | 0.2-0.3 | 0.1-0.2 | 0.2-0.4 |
| **SOUTH (11)** | 0.6-0.8 | 0.2-0.3 | 0.1-0.2 | 0.2-0.4 |

**Detailed WE SF Table:**

| State | Code | SF Range | Typical SF | SF Level |
|-------|------|----------|------------|----------|
| (WE, NORTH, WINTER) | 11 00 00 | 0.6-0.8 | 0.70 | 🟠 High |
| (WE, NORTH, AUTUMN) | 11 00 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (WE, NORTH, SUMMER) | 11 00 10 | 0.2-0.3 | 0.25 | 🟢 Low |
| (WE, NORTH, SPRING) | 11 00 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (WE, WEST, WINTER) | 11 01 00 | 0.7-0.9 | 0.80 | 🔴 Critical |
| (WE, WEST, AUTUMN) | 11 01 01 | 0.2-0.4 | 0.30 | 🟢 Low |
| (WE, WEST, SUMMER) | 11 01 10 | 0.1-0.3 | 0.20 | 🟢 Very Low |
| (WE, WEST, SPRING) | 11 01 11 | 0.3-0.5 | 0.40 | 🟡 Moderate |
| (WE, EAST, WINTER) | 11 10 00 | 0.5-0.7 | 0.60 | 🟠 High |
| (WE, EAST, AUTUMN) | 11 10 01 | 0.2-0.3 | 0.25 | 🟢 Low |
| (WE, EAST, SUMMER) | 11 10 10 | 0.1-0.2 | 0.15 | 🟢 Very Low |
| (WE, EAST, SPRING) | 11 10 11 | 0.2-0.4 | 0.30 | 🟢 Low |
| (WE, SOUTH, WINTER) | 11 11 00 | 0.6-0.8 | 0.70 | 🟠 High |
| (WE, SOUTH, AUTUMN) | 11 11 01 | 0.2-0.3 | 0.25 | 🟢 Low |
| (WE, SOUTH, SUMMER) | 11 11 10 | 0.1-0.2 | 0.15 | 🟢 Very Low |
| (WE, SOUTH, SPRING) | 11 11 11 | 0.2-0.4 | 0.30 | 🟢 Low |

---

## 3. Visual SF Heatmap (3D Representation)

### 3.1. Color Scale

| SF Range | Color | Level | Interpretation |
|----------|-------|-------|----------------|
| 0.0-0.2 | 🟢 Very Low | 1 | Highly coherent |
| 0.2-0.3 | 🟢 Low | 2 | Well-aligned |
| 0.3-0.4 | 🟡 Moderate-Low | 3 | Some tension |
| 0.4-0.5 | 🟡 Moderate | 4 | Significant tension |
| 0.5-0.6 | 🟠 Moderate-High | 5 | Stressed |
| 0.6-0.7 | 🟠 High | 6 | Unstable |
| 0.7-0.8 | 🔴 Very High | 7 | Critical |
| 0.8-1.0 | 🔴 Critical | 8 | Implosion risk |

### 3.2. Heatmap by Agency (Layer View)

**Layer 1: THEY States (A = 00)**

```
        WINTER  AUTUMN  SUMMER  SPRING
         (00)    (01)    (11)    (10)
NORTH(00)  🔴     🟡     🟢     🟡
WEST (01)  🔴     🟢     🟢     🟡
EAST (10)  🟠     🟢     🟢     🟡
SOUTH(11)  🔴     🟢     🟢     🟡
```

**Layer 2: YOU States (A = 01)**

```
        WINTER  AUTUMN  SUMMER  SPRING
         (00)    (01)    (11)    (10)
NORTH(00)  🔴     🟡     🟢     🟡
WEST (01)  🔴     🟢     🟢     🟡
EAST (10)  🟠     🟢     🟢     🟡
SOUTH(11)  🔴     🟢     🟢     🟡
```

**Layer 3: ME States (A = 10)**

```
        WINTER  AUTUMN  SUMMER  SPRING
         (00)    (01)    (11)    (10)
NORTH(00)  🔴     🟢     🟢     🟡
WEST (01)  🔴     🟢     🟢     🟡
EAST (10)  🟠     🟢     🟢     🟢
SOUTH(11)  🔴     🟢     🟢     🟡
```

**Layer 4: WE States (A = 11)**

```
        WINTER  AUTUMN  SUMMER  SPRING
         (00)    (01)    (11)    (10)
NORTH(00)  🟠     🟢     🟢     🟡
WEST (01)  🔴     🟢     🟢     🟡
EAST (10)  🟠     🟢     🟢     🟢
SOUTH(11)  🟠     🟢     🟢     🟢
```

---

## 4. SF Distribution Analysis

### 4.1. Overall Distribution

| SF Range | Level | Count | Percentage |
|----------|-------|-------|------------|
| 0.0-0.2 | Very Low | 8 | 12.5% |
| 0.2-0.3 | Low | 24 | 37.5% |
| 0.3-0.4 | Moderate-Low | 12 | 18.75% |
| 0.4-0.5 | Moderate | 8 | 12.5% |
| 0.5-0.6 | Moderate-High | 4 | 6.25% |
| 0.6-0.7 | High | 4 | 6.25% |
| 0.7-0.8 | Very High | 0 | 0% |
| 0.8-1.0 | Critical | 4 | 6.25% |

### 4.2. Distribution by Agency

| Agency | Avg SF | Min SF | Max SF | Std Dev |
|--------|--------|--------|--------|---------|
| **THEY (00)** | 0.41 | 0.15 | 0.90 | 0.24 |
| **YOU (01)** | 0.42 | 0.20 | 0.90 | 0.22 |
| **ME (10)** | 0.39 | 0.20 | 0.80 | 0.20 |
| **WE (11)** | 0.33 | 0.15 | 0.80 | 0.18 |

### 4.3. Distribution by Vector

| Vector | Avg SF | Min SF | Max SF |
|--------|--------|--------|--------|
| **EAST (10)** | 0.34 | 0.15 | 0.70 |
| **SOUTH (11)** | 0.35 | 0.15 | 0.80 |
| **WEST (01)** | 0.38 | 0.20 | 0.90 |
| **NORTH (00)** | 0.45 | 0.25 | 0.90 |

### 4.4. Distribution by Phase

| Phase | Avg SF | Min SF | Max SF |
|-------|--------|--------|--------|
| **SPRING (10)** | 0.40 | 0.30 | 0.50 |
| **SUMMER (11)** | 0.22 | 0.15 | 0.30 |
| **AUTUMN (01)** | 0.30 | 0.25 | 0.40 |
| **WINTER (00)** | 0.78 | 0.60 | 0.90 |

---

## 5. Lowest SF States (The "Coherent Zone")

| Rank | State | Code | SF | Category |
|------|-------|------|-----|----------|
| 1 | (WE, EAST, SUMMER) | 11 10 10 | 0.15 | Tech Scaling Team |
| 1 | (WE, SOUTH, SUMMER) | 11 11 10 | 0.15 | Market Scaling Team |
| 3 | (THEY, SOUTH, SUMMER) | 00 11 10 | 0.15 | Growing Marketplace |
| 3 | (THEY, EAST, SUMMER) | 00 10 10 | 0.20 | Growing Platform |
| 5 | (WE, WEST, SUMMER) | 11 01 10 | 0.20 | Growing Fund |
| 5 | (ME, SOUTH, SUMMER) | 10 11 10 | 0.20 | Successful Individual |
| 5 | (YOU, SOUTH, SUMMER) | 01 11 10 | 0.20 | Loyal Client |

---

## 6. Highest SF States (The "Danger Zone")

| Rank | State | Code | SF | Category |
|------|-------|------|-----|----------|
| 64 | (THEY, NORTH, WINTER) | 00 00 00 | 0.90 | Dying Institution |
| 64 | (THEY, WEST, WINTER) | 00 01 00 | 0.90 | Collapsed Finance |
| 64 | (YOU, WEST, WINTER) | 01 01 00 | 0.90 | Defaulting Debtor |
| 63 | (THEY, SOUTH, WINTER) | 00 11 00 | 0.80 | Dying Marketplace |
| 63 | (YOU, NORTH, WINTER) | 01 00 00 | 0.80 | Sanctioned Client |
| 63 | (YOU, SOUTH, WINTER) | 01 11 00 | 0.80 | Lost Customer |
| 63 | (ME, NORTH, WINTER) | 10 00 00 | 0.80 | Agency Liquidator |
| 63 | (ME, WEST, WINTER) | 10 01 00 | 0.80 | Asset Liquidator |
| 63 | (ME, SOUTH, WINTER) | 10 11 00 | 0.80 | Bankruptcy Trustee |
| 63 | (WE, WEST, WINTER) | 11 01 00 | 0.80 | Liquidation Fund |

---

## 7. SF Tensor Components

### 7.1. Agency Self-Consistency Δ_agency(a)

| Agency | Δ_agency | Rationale |
|--------|----------|-----------|
| **ME (10)** | 0.2 | Individuals flexible but limited |
| **WE (11)** | 0.1 | Teams naturally coherent |
| **YOU (01)** | 0.3 | Client-centric creates dependency tension |
| **THEY (00)** | 0.2 | Systems coherent but inert |

### 7.2. Vector Self-Consistency Δ_vector(v)

| Vector | Δ_vector | Rationale |
|--------|----------|-----------|
| **EAST (10)** | 0.3 | Innovation inherently risky, unstable |
| **SOUTH (11)** | 0.1 | Markets provide clear feedback |
| **WEST (01)** | 0.2 | Capital accumulation stable but competitive |
| **NORTH (00)** | 0.3 | Regulation creates structural rigidity |

### 7.3. Phase Self-Consistency Δ_phase(t)

| Phase | Δ_phase | Rationale |
|-------|---------|-----------|
| **SPRING (10)** | 0.4 | Creation phase chaotic, uncertain |
| **SUMMER (11)** | 0.1 | Growth phase naturally aligned |
| **AUTUMN (01)** | 0.2 | Optimization phase stable |
| **WINTER (00)** | 0.5 | Decline phase inherently disruptive |

### 7.4. Pairwise Mismatch Matrix Δ_pairwise

**Agency-Vector Mismatch:**

| A\V | EAST (10) | SOUTH (11) | WEST (01) | NORTH (00) |
|-----|-----------|------------|-----------|------------|
| **ME (10)** | 0.1 | 0.2 | 0.3 | 0.5 |
| **WE (11)** | 0.1 | 0.1 | 0.2 | 0.4 |
| **YOU (01)** | 0.3 | 0.2 | 0.1 | 0.4 |
| **THEY (00)** | 0.2 | 0.1 | 0.2 | 0.1 |

**Vector-Phase Mismatch:**

| V\T | SPRING (10) | SUMMER (11) | AUTUMN (01) | WINTER (00) |
|-----|-------------|-------------|-------------|-------------|
| **EAST (10)** | 0.2 | 0.1 | 0.3 | 0.6 |
| **SOUTH (11)** | 0.3 | 0.1 | 0.2 | 0.5 |
| **WEST (01)** | 0.3 | 0.2 | 0.1 | 0.5 |
| **NORTH (00)** | 0.4 | 0.3 | 0.2 | 0.2 |

**Phase-Agency Mismatch:**

| T\A | ME (10) | WE (11) | YOU (01) | THEY (00) |
|-----|---------|---------|----------|-----------|
| **SPRING (10)** | 0.2 | 0.2 | 0.3 | 0.4 |
| **SUMMER (11)** | 0.2 | 0.1 | 0.2 | 0.2 |
| **AUTUMN (01)** | 0.2 | 0.1 | 0.2 | 0.2 |
| **WINTER (00)** | 0.5 | 0.4 | 0.5 | 0.3 |

---

## 8. SF Gradients

### 8.1. Phase Gradient (Average SF by Phase)

```
SF
0.8 |                    🔴 WINTER (0.78)
0.7 |
0.6 |
0.5 |
0.4 |        🟡 SPRING (0.40)
0.3 |              🟢 AUTUMN (0.30)
0.2 |                    🟢 SUMMER (0.22)
0.1 |
0.0 +--------------------------------
      SPRING  AUTUMN  SUMMER  WINTER
```

### 8.2. Agency Gradient (Average SF by Agency)

```
SF
0.5 |
0.4 |    🟡 YOU (0.42)  🟡 THEY (0.41)  🟡 ME (0.39)
0.3 |                          🟢 WE (0.33)
0.2 |
0.1 |
0.0 +--------------------------------
      YOU     THEY    ME      WE
```

### 8.3. Vector Gradient (Average SF by Vector)

```
SF
0.5 |                    🟡 NORTH (0.45)
0.4 |              🟡 WEST (0.38)
0.3 |        🟢 SOUTH (0.35)  🟢 EAST (0.34)
0.2 |
0.1 |
0.0 +--------------------------------
      NORTH   WEST    SOUTH   EAST
```

---

## 9. Strategic Implications

### 9.1. Low SF Zones (Target States)

States with SF < 0.3 are structurally coherent and desirable:
- **All SUMMER phase states** (especially with EAST or SOUTH vectors)
- **WE agency** with any vector in SUMMER or AUTUMN
- **EAST vector** with WE or THEY agency in SUMMER

### 9.2. High SF Zones (Avoid or Transform)

States with SF > 0.6 require immediate attention:
- **All WINTER phase states** (regardless of agency/vector)
- **NORTH vector** in WINTER (especially with YOU or ME agency)
- **WEST vector** in WINTER (especially with YOU agency)

### 9.3. SF-CES Correlation

| SF Range | Avg CES | Relationship |
|----------|---------|--------------|
| 0.0-0.2 | 78 | Strong negative correlation |
| 0.2-0.3 | 65 | (r ≈ -0.85) |
| 0.3-0.4 | 52 | |
| 0.4-0.5 | 41 | |
| 0.5-0.6 | 30 | |
| 0.6-0.7 | 22 | |
| 0.7-0.8 | 15 | |
| 0.8-1.0 | 8 | |

---

## 10. SF Formula Reference

For quick calculation:

```
SF(ω) = (Δ_agency + Δ_vector + Δ_phase + 2·Δ_pairwise) / 5
```

**Component lookup:**

| Agency | Δ_agency | Vector | Δ_vector | Phase | Δ_phase |
|--------|----------|--------|----------|-------|----------|
| ME (10) | 0.2 | EAST (10) | 0.3 | SPRING (10) | 0.4 |
| WE (11) | 0.1 | SOUTH (11) | 0.1 | SUMMER (11) | 0.1 |
| YOU (01) | 0.3 | WEST (01) | 0.2 | AUTUMN (01) | 0.2 |
| THEY (00) | 0.2 | NORTH (00) | 0.3 | WINTER (00) | 0.5 |

**Δ_pairwise** = average of:
- Agency-Vector mismatch (from Table 7.4)
- Vector-Phase mismatch (from Table 7.4)
- Phase-Agency mismatch (from Table 7.4)

---

## 11. Summary

| Metric | Value |
|--------|-------|
| **Lowest SF state** | (WE, EAST, SUMMER) — 0.15 |
| **Highest SF state** | (THEY, NORTH, WINTER) — 0.90 |
| **Average SF across Ω** | 0.39 |
| **Best phase** | SUMMER (avg 0.22) |
| **Best agency** | WE (avg 0.33) |
| **Best vector** | EAST (avg 0.34) |
| **Worst phase** | WINTER (avg 0.78) |

**Key Insight:** The structural friction tensor reveals that coherence is not uniformly distributed — certain configurations are inherently more aligned. The most coherent states combine team agency with innovation or market vectors during growth phases, while the most conflicted states involve any agency in winter phase, especially with regulatory or capital vectors.

---

*This document provides the complete structural friction tensor for Economic Geometry, serving as a reference for evaluating internal coherence and identifying states requiring transformation.*
