# TRAJECTORY PREDICTION: Forecasting Business Paths in Ω

**Document Version:** 1.0
**Canonical Reference:** SUBIT v9.0+
**Relation to Monograph:** Chapter 6, Section 6.3

---

## 1. Introduction to Trajectory Prediction

In Economic Geometry, **trajectory prediction** is the art and science of forecasting how a business will move through the state space Ω over time. Just as celestial mechanics predicts the orbits of planets, economic geometry predicts the paths of business configurations.

**Definition 1.1 (Trajectory).** A trajectory is a sequence of states γ = (ω₀, ω₁, ω₂, ..., ωₖ) representing the evolution of a business over time, where each consecutive pair may or may not be adjacent in Ω.

---

## 2. Types of Trajectories

### 2.1. Natural Trajectories

**Definition 2.1 (Natural Trajectory).** A natural trajectory follows the gradient of CES, moving toward states with higher capital efficiency:

```
ω(t+Δt) = argmax_{ω' : d(ω,ω')=1} CES(ω')
```

**Example 2.1.** For (ME, EAST, SPRING) = 10 10 10:
- Neighbors and their CES:
  - (WE, EAST, SPRING): CES = 58
  - (ME, SOUTH, SPRING): CES = 46
  - (ME, EAST, SUMMER): CES = 65
- Natural move: to (ME, EAST, SUMMER) (highest CES)

### 2.2. Forced Trajectories

**Definition 2.2 (Forced Trajectory).** A forced trajectory is driven by external factors (market pressure, competition, regulation) that override the natural CES gradient.

**Example 2.2.** A company at (WE, SOUTH, SUMMER) with CES=93 might be forced by competition to move to (WE, EAST, SUMMER) even though its CES is lower (88), to maintain competitive advantage.

### 2.3. Optimal Trajectories

**Definition 2.3 (Optimal Trajectory).** An optimal trajectory maximizes some objective function over a time horizon, such as:

```
max_{γ} Σᵢ CES(ωᵢ) - λ·Σᵢ d(ωᵢ, ωᵢ₊₁)
```

This balances immediate efficiency against transition costs.

### 2.4. Stochastic Trajectories

**Definition 2.4 (Stochastic Trajectory).** A stochastic trajectory incorporates randomness in transitions:

```
P(ω → ω') = f(ω, ω', external factors)
```

---

## 3. The Canonical Startup Trajectory

### 3.1. The Classic Path

The most well-studied trajectory in Economic Geometry is the canonical startup lifecycle:

| Stage | State | Code | CES | SF | Description |
|-------|-------|------|-----|-----|-------------|
| 1 | (ME, EAST, SPRING) | 10 10 10 | 42 | 0.2 | Solo inventor in garage |
| 2 | (WE, EAST, SPRING) | 11 10 10 | 58 | 0.18 | Team formed, still in creation |
| 3 | (WE, EAST, SUMMER) | 11 10 11 | 82 | 0.12 | Tech startup in growth |
| 4 | (WE, SOUTH, SUMMER) | 11 11 11 | 93 | 0.1 | Market expansion, scaling |
| 5 | (WE, SOUTH, AUTUMN) | 11 11 01 | 76 | 0.18 | Maturity, optimization |
| 6 | (WE, WEST, AUTUMN) | 11 01 01 | 71 | 0.22 | Capital focus |
| 7 | (THEY, WEST, AUTUMN) | 00 01 01 | 68 | 0.25 | Institutionalization |
| 8 | (THEY, NORTH, AUTUMN) | 00 00 01 | 52 | 0.35 | Regulatory engagement |
| 9 | (THEY, NORTH, WINTER) | 00 00 00 | 0 | 0.9 | Decline |
| 10 | (ME, EAST, SPRING) | 10 10 10 | 42 | 0.2 | Reinvention (if successful) |

### 3.2. Visualization

```
CES
^
93 |           * (4)
82 |       * (3)
76 |           * (5)
71 |               * (6)
68 |               * (7)
58 |   * (2)
52 |                   * (8)
42 | * (1)                         * (10)
0  |                       * (9)
   +----------------------------------------> Time
    1   2   3   4   5   6   7   8   9   10
```

### 3.3. Key Insights

1. **Peak CES** occurs at stage 4 (WE, SOUTH, SUMMER)
2. **Decline** is gradual after the peak
3. **Reinvention** requires returning to stage 1
4. **Not all companies** follow this exact path

---

## 4. Alternative Trajectories

### 4.1. The Innovation-First Path

| Stage | State | Description |
|-------|-------|-------------|
| 1 | (ME, EAST, SPRING) | Solo inventor |
| 2 | (WE, EAST, SPRING) | Team forms |
| 3 | (WE, EAST, SUMMER) | Tech growth |
| 4 | (WE, EAST, AUTUMN) | Tech optimization |
| 5 | (THEY, EAST, AUTUMN) | Platform/ecosystem |
| 6 | (THEY, EAST, WINTER) | Obsolescence |

Instead of moving to market (SOUTH), this path stays in innovation (EAST) throughout.

### 4.2. The Market-First Path

| Stage | State | Description |
|-------|-------|-------------|
| 1 | (ME, SOUTH, SPRING) | Solo market entrant |
| 2 | (WE, SOUTH, SPRING) | Team builds |
| 3 | (WE, SOUTH, SUMMER) | Market scaling |
| 4 | (WE, SOUTH, AUTUMN) | Market optimization |
| 5 | (THEY, SOUTH, AUTUMN) | Marketplace |
| 6 | (THEY, SOUTH, WINTER) | Market decline |

### 4.3. The Capital-First Path

| Stage | State | Description |
|-------|-------|-------------|
| 1 | (ME, WEST, SPRING) | Angel investor |
| 2 | (WE, WEST, SPRING) | Fund formed |
| 3 | (WE, WEST, SUMMER) | Active investing |
| 4 | (WE, WEST, AUTUMN) | Harvesting |
| 5 | (THEY, WEST, AUTUMN) | Institution |
| 6 | (THEY, WEST, WINTER) | Collapse |

### 4.4. The Regulatory Path

| Stage | State | Description |
|-------|-------|-------------|
| 1 | (ME, NORTH, SPRING) | Activist/lobbyist |
| 2 | (WE, NORTH, SPRING) | Organization forms |
| 3 | (WE, NORTH, SUMMER) | Influence grows |
| 4 | (WE, NORTH, AUTUMN) | Established regulator |
| 5 | (THEY, NORTH, AUTUMN) | Bureaucracy |
| 6 | (THEY, NORTH, WINTER) | Dissolution |

---

## 5. Trajectory Prediction Methods

### 5.1. Gradient Ascent (Natural Movement)

**Algorithm 5.1 (Greedy Gradient Ascent).**
```
ω_current = initial state
while not converged:
    neighbors = {ω' : d(ω_current, ω') = 1}
    ω_next = argmax_{ω' in neighbors} CES(ω')
    if CES(ω_next) <= CES(ω_current): break
    ω_current = ω_next
```

**Limitations:**
- Gets stuck at local maxima
- Ignores long-term optimization
- Doesn't account for external forces

### 5.2. Global Optimization

**Algorithm 5.2 (Trajectory Optimization).**
```
Find path γ = (ω₀, ω₁, ..., ωₖ) maximizing:
    J(γ) = Σᵢ CES(ωᵢ) - λ·Σᵢ d(ωᵢ, ωᵢ₊₁)
subject to: ω₀ given, ωₖ free, d(ωᵢ, ωᵢ₊₁) ≤ 1
```

This is a dynamic programming problem on the graph of Ω.

### 5.3. Markov Chain Models

**Definition 5.1 (Transition Matrix).** P is a 64×64 matrix where P_{ij} = P(ω_i → ω_j).

**Properties:**
- Σⱼ P_{ij} = 1
- P_{ij} > 0 only if d(ω_i, ω_j) ≤ 1 (or sometimes larger jumps allowed)
- Stationary distribution π satisfies πP = π

**Example 5.1.** For a startup with probability p of moving to higher CES states and (1-p) of staying:

```
P(ω → ω') = p / |{ω' : CES(ω') > CES(ω)}|  for ω' with higher CES
P(ω → ω) = 1-p
P(ω → ω') = 0 for ω' with lower CES
```

### 5.4. Machine Learning Approaches

**Features for prediction:**
- Current state ω
- Recent trajectory history
- External factors (market conditions, competition)
- Company-specific parameters (size, age, industry)

**Models:**
- Recurrent neural networks (RNNs) for sequence prediction
- Hidden Markov Models (HMMs) with latent states
- Reinforcement learning for optimal path discovery

---

## 6. Attractors and Repellors

### 6.1. Attractor States

**Definition 6.1 (Attractor).** A state ω* is an attractor if trajectories tend to converge to it:

```
∀ ω in basin of attraction, lim_{t→∞} ω(t) = ω*
```

**Examples of attractors in Ω:**

| Attractor | CES | Basin Size | Description |
|-----------|-----|------------|-------------|
| (WE, SOUTH, SUMMER) | 93 | Large | Growth-stage success |
| (THEY, SOUTH, AUTUMN) | 76 | Medium | Mature marketplace |
| (WE, EAST, SUMMER) | 82 | Medium | Tech success |
| (THEY, NORTH, WINTER) | 0 | Small | Terminal decline |

### 6.2. Repellor States

**Definition 6.2 (Repellor).** A state ω* is a repellor if trajectories tend to move away from it.

**Examples:**
- (ME, NORTH, WINTER) — highly unstable
- (YOU, NORTH, WINTER) — client in regulatory decline
- (THEY, EAST, WINTER) — platform with obsolete technology

### 6.3. Limit Cycles

**Definition 6.3 (Limit Cycle).** A limit cycle is a closed trajectory that repeats periodically.

**Example 6.1.** Some businesses cycle between:
- (WE, EAST, SUMMER) → (WE, SOUTH, SUMMER) → (WE, EAST, SUMMER)
Innovation phase followed by market phase, repeating.

---

## 7. Empirical Trajectories: Case Studies

### 7.1. Amazon's Trajectory

| Year | State | Code | Event |
|------|-------|------|-------|
| 1994 | (ME, EAST, SPRING) | 10 10 10 | Bezos in garage |
| 1997 | (WE, EAST, SUMMER) | 11 10 11 | IPO, scaling technology |
| 2000 | (WE, SOUTH, SUMMER) | 11 11 11 | Marketplace expansion |
| 2006 | (THEY, SOUTH, SUMMER) | 00 11 11 | AWS launch, platformization |
| 2015 | (THEY, SOUTH, AUTUMN) | 00 11 01 | Maturity, optimization |
| 2020 | (THEY, WEST, AUTUMN) | 00 01 01 | Capital focus, acquisitions |

**Key insight:** Amazon followed the canonical trajectory but stayed in SUMMER longer than typical.

### 7.2. Apple's Trajectory

| Year | State | Code | Event |
|------|-------|------|-------|
| 1976 | (WE, EAST, SPRING) | 11 10 10 | Apple I in garage (already team) |
| 1980 | (WE, EAST, SUMMER) | 11 10 11 | IPO, Apple II success |
| 1985 | (ME, EAST, AUTUMN) | 10 10 01 | Jobs leaves, Sculley optimizes |
| 1997 | (THEY, EAST, WINTER) | 00 10 00 | Near bankruptcy |
| 1998 | (WE, EAST, SPRING) | 11 10 10 | Jobs returns, reinvention |
| 2007 | (WE, SOUTH, SUMMER) | 11 11 11 | iPhone launch, market dominance |
| 2011+ | (THEY, SOUTH, AUTUMN) | 00 11 01 | Mature ecosystem |

**Key insight:** Apple demonstrated a complete cycle of death and rebirth.

### 7.3. Kodak's Trajectory (Failure)

| Year | State | Code | Event |
|------|-------|------|-------|
| 1975 | (THEY, EAST, SPRING) | 00 10 10 | Digital camera invented |
| 1980 | (THEY, EAST, SUMMER) | 00 10 11 | Technology leadership |
| 1990 | (THEY, NORTH, AUTUMN) | 00 00 01 | Focus on patents, regulations |
| 2000 | (THEY, NORTH, WINTER) | 00 00 00 | Decline |
| 2012 | Bankruptcy | — | End |

**Key insight:** Kodak's fatal move was EAST → NORTH instead of EAST → SOUTH, choosing regulation over market.

---

## 8. Trajectory Prediction for Decision Making

### 8.1. Early Warning Signs

Indicators that a trajectory is about to change:

| Indicator | What It Means |
|-----------|---------------|
| SF increasing for 3+ periods | Approaching instability |
| CES plateau | Growth ceiling reached |
| Multiple neighbors with similar CES | Bifurcation approaching |
| External shocks | Possible forced transition |

### 8.2. What-If Analysis

Given current state ω, simulate possible futures:

```
For each possible operator T ∈ G:
    ω' = T(ω)
    Predict subsequent trajectory γ(ω')
    Estimate outcomes (final CES, time to reach, resources needed)
```

### 8.3. Optimal Path Selection

Given current state ω and goal state ω_goal:

1. Find all geodesics between ω and ω_goal
2. For each geodesic, compute path friction Σ SF(γᵢ)
3. Select geodesic with minimum path friction
4. Consider quasi-geodesics if all geodesics have high friction

---

## 9. Mathematical Formulation

### 9.1. Discrete-Time Dynamics

```
ω(t+1) = F(ω(t), u(t), ξ(t))
```

where:
- u(t) is control input (strategic decisions)
- ξ(t) is random noise (market fluctuations)

### 9.2. Continuous-Time Analogy

For theoretical purposes, we can consider a continuous analog:

```
dω/dt = ∇CES(ω) + external forces + noise
```

But since Ω is discrete, this requires interpolation.

### 9.3. Path Integrals

The probability of a trajectory γ = (ω₀, ω₁, ..., ωₖ) is:

```
P(γ) = Π_{t=0}^{k-1} P(ω_t → ω_{t+1})
```

The most probable trajectory maximizes log P(γ).

---

## 10. Summary Table

| Trajectory Type | Driver | Example |
|-----------------|--------|---------|
| **Natural** | CES gradient | (ME,EAST,SPRING) → (ME,EAST,SUMMER) |
| **Forced** | External pressure | (WE,SOUTH,SUMMER) → (WE,EAST,SUMMER) under competition |
| **Optimal** | Long-term planning | Multi-step path balancing gains and costs |
| **Stochastic** | Random factors | Probabilistic transitions |
| **Cyclic** | Repeating pattern | Innovation ↔ Market oscillation |
| **Terminal** | End state | (THEY,NORTH,WINTER) |

**Key Insight:** Trajectory prediction in Economic Geometry combines gradient-based natural movement with external forces and strategic choices. By understanding the landscape of Ω and the dynamics of transitions, we can forecast likely paths and identify optimal trajectories.

---

*This document establishes trajectory prediction in Economic Geometry, providing the foundation for forecasting business evolution and planning strategic moves.*
