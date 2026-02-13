# Gauge Symmetry

The Standard Model is built on the principle of **local gauge invariance** under the symmetry group:

$$SU(3)_C \times SU(2)_L \times U(1)_Y$$

This single mathematical requirement — that the laws of physics must remain unchanged under independent symmetry transformations at every point in spacetime — fixes almost the entire structure of the forces and interactions in the [[Standard model of particle physics|Standard Model]].

## What gauge symmetry means

A **global** symmetry means the physics is unchanged if the same transformation is applied everywhere at once. A **local** (gauge) symmetry demands invariance even when the transformation varies from point to point in spacetime.

Enforcing local invariance requires introducing new fields — the **gauge fields** — that compensate for the varying transformation. These gauge fields are exactly the force-carrying particles:

| Symmetry group | Force | Gauge bosons |
|---------------|-------|-------------|
| $SU(3)_C$ | [[Strong Force]] (QCD) | 8 gluons |
| $SU(2)_L$ | [[Weak Force]] (part of electroweak) | $W^1, W^2, W^3$ |
| $U(1)_Y$ | Hypercharge (part of electroweak) | $B$ |

After [[Higgs Mechanism|electroweak symmetry breaking]], the $SU(2)_L \times U(1)_Y$ bosons mix into the physical particles: $W^\pm$, $Z^0$, and the photon $\gamma$. See [[Gauge Bosons]].

## The three symmetry groups

### $SU(3)_C$ — Color
- Acts on the "color" charge of [[Quarks]] (red, green, blue)
- 8 generators → 8 gluons, which themselves carry color charge
- Non-abelian: gluons interact with each other, leading to confinement and asymptotic freedom
- See [[Strong Force]]

### $SU(2)_L$ — Weak isospin
- Acts only on **left-handed** fermions (hence the subscript $L$), pairing them into doublets (e.g. $\begin{pmatrix} \nu_e \\ e^- \end{pmatrix}_L$)
- 3 generators → 3 gauge bosons ($W^1, W^2, W^3$)
- Non-abelian: the $W$ bosons interact with each other
- See [[Weak Force]]

### $U(1)_Y$ — Hypercharge
- Acts on all fermions, assigning each a hypercharge quantum number $Y$
- 1 generator → 1 gauge boson ($B$)
- Abelian: the $B$ boson does not self-interact
- After symmetry breaking, combines with $W^3$ to produce the photon and the $Z^0$
- See [[Electromagnetic Force]]

## Why gauge symmetry matters

- **Determines interactions**: The form of every vertex in the Standard Model — which particles interact, with what strength — follows from the gauge symmetry. You do not choose the interactions; the symmetry dictates them.
- **Ensures renormalizability**: Gauge symmetry provides the cancellations needed to make the theory mathematically consistent at all energies (perturbatively).
- **Predicts gauge bosons**: The existence of gluons, W, Z, and the photon is a *consequence* of the symmetry, not an assumption.
- **Constrains [[The Lagrangian]]**: Only gauge-invariant terms are allowed in the Lagrangian, enormously restricting the possible physics.

## Mathematical context

The symmetry groups $SU(N)$ are Lie groups — continuous groups of unitary matrices with unit determinant. Their structure is encoded in **Lie algebras**, with generators satisfying commutation relations that determine the self-interactions of the gauge bosons.

For the mathematical background on Lie groups and algebras, see [[Some math|Mathematical Foundations]].

## Connections

- [[Standard model of particle physics]] — gauge symmetry as a core assumption
- [[The Lagrangian]] — built from gauge-invariant terms
- [[Higgs Mechanism]] — breaks $SU(2)_L \times U(1)_Y \to U(1)_{\text{EM}}$
- [[Gauge Bosons]] — the force carriers required by gauge invariance
- [[Strong Force]], [[Weak Force]], [[Electromagnetic Force]] — the three gauge interactions
- [[Some math|Mathematical Foundations]] — Lie groups and Lie algebras
