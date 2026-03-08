# economic-geometry

### Formal Foundation v1.0 — The Geometry of Economic States

A rigorous mathematical framework for representing, analyzing, and transforming business configurations within a 64-state semantic space.

* * *

## 📐 Overview

**Economic Geometry** is a formal theory that treats economic agents, capital, and business models as geometric objects in a multidimensional state space. It provides the mathematical foundation for the SUBIT-64 ontology and enables structural analysis of business configurations.

### Fundamental Theorem

Every economic entity can be uniquely represented as a vector **ω** in the product space:

**Ω = A × V × T**

where:
- **A** (WHO — Agency) = {ME, WE, YOU, THEY}
- **V** (WHERE — Vector) = {EAST, SOUTH, WEST, NORTH}
- **T** (WHEN — Phase) = {SPRING, SUMMER, AUTUMN, WINTER}

This yields **|Ω| = 64 canonical states**, isomorphic to the 6-bit cube **{0,1}⁶**.

* * *

## 📁 Repository Structure

```
economic-geometry/
│
├── README.md                           # This file
├── LICENSE                             # MIT License
├── CITATION.cff                        # Citation metadata for academic use
│
├── axioms/                             # Foundational principles
│   ├── space-definition.md             # Ω = A × V × T: proof of completeness
│   ├── orthogonality-proof.md          # Independence of WHO, WHERE, WHEN
│   └── binary-isomorphism.md           # {0,1}⁶ mapping and Anima/Animus duality
│
├── geometry/                            # Mathematical structure
│   ├── metric-space.md                  # Hamming distance, structural friction SF(ω)
│   ├── geodesics.md                      # Optimal transformation paths
│   ├── observables.md                    # CES, risk, monetization as functionals
│   └── symmetry-group.md                  # Transformation operators T: Ω → Ω
│
├── dynamics/                             # Evolution and change
│   ├── transformation-operators.md        # Scale, Pivot, Harvest, etc.
│   ├── phase-transitions.md                # First and second-order transitions
│   ├── bifurcation-theory.md                # Critical points and instability
│   └── trajectory-prediction.md              # Forecasting business paths
│
├── atlas/                                # Complete mapping of Ω
│   ├── subit-64-catalog.md                # All 64 states with descriptions
│   ├── capital-efficiency-heatmap.md       # CES values across Ω
│   ├── structural-friction-tensor.md       # SF(ω) for all configurations
│   └── risk-profiles/                       # Detailed risk analysis per region
│       ├── quadrant-1.md
│       ├── quadrant-2.md
│       └── ...
│
├── applications/                          # Practical implementations
│   ├── business-diagnostics/                # How to identify ω for real companies
│   │   ├── methodology.md
│   │   └── case-studies/
│   │       ├── amazon-trajectory.md
│   │       ├── tesla-evolution.md
│   │       └── startup-failures.md
│   ├── portfolio-theory.md                   # Diversification as dispersion in Ω
│   ├── investment-criteria.md                 # Geometric due diligence
│   └── policy-framework.md                     # National economic cartography
│
├── extensions/                             # Advanced topics
│   ├── n-dimensional-generalization.md      # Ωₙ beyond 3 dimensions
│   ├── quantum-analogies.md                  # Superposition of business states
│   ├── fractal-hierarchy.md                   # Self-similarity across scales
│   └── category-theory-foundations.md          # Functorial approaches
│
└── implementations/                         # Computational tools
    ├── python/
    └──  README.md
        ├── omega_space.py
        ├── metrics.py
        ├── transformers.py
        └──  visualization/
            ├── lattice-3d.py
            └── trajectory-plotter.py

```

* * *

## 🎯 Key Contributions

| Concept | Symbol | Definition |
|:--------|:-------|:-----------|
| **State Space** | Ω | A × V × T, the complete economic configuration space |
| **State Vector** | ω | (a, v, t), a point representing a business configuration |
| **Structural Distance** | d(ω₁, ω₂) | Hamming distance between states |
| **Structural Friction** | SF(ω) | Internal inconsistency measure |
| **Capital Efficiency** | CES(ω) | (Fₗ × M_v × Pₜ) - SF, the principal observable |
| **Transformation** | T: Ω → Ω | Operators representing business evolution |

* * *

## 🔗 Relationship with SUBIT-Omega-Analyzer

This repository provides the **mathematical foundation** for the [SUBIT-Omega-Analyzer](https://github.com/sciganec/subit-omega-analyzer) tool:

| Repository | Purpose |
|:-----------|:--------|
| **economic-geometry** | Formal theory, axioms, proofs, mathematical structure |
| subit-omega-analyzer | Practical implementation, prompts, business diagnostics |

* * *

## 📖 Getting Started

1.  Begin with the [axioms/space-definition.md](axioms/space-definition.md)
2.  Explore the [atlas/subit-64-catalog.md](atlas/subit-64-catalog.md) to understand all 64 states
3.  Study [geometry/metric-space.md](geometry/metric-space.md) for the mathematical core
4.  See [applications/business-diagnostics/methodology.md](applications/business-diagnostics/methodology.md) for practical use

* * *

## 🧑‍🤝‍🧑 How to Contribute

We welcome contributions from mathematicians, economists, entrepreneurs, and philosophers. See [community/contributing.md](community/contributing.md) for guidelines.

**Current priorities:**
- Formal proofs of completeness theorems
- Empirical validation studies
- Python implementation of core calculus
- Case study documentation

* * *

## 📄 License

MIT License

* * *

## 🧬 Version

**v1.0 — Geometric Foundation** (March 2026)
- Axiomatic definition of Ω-space
- Complete metric structure
- Transformation group specification
- Full atlas of 64 states

* * *

