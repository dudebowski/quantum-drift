# Tensors

Tensors are a natural extension of scalars and vectors, motivated by physical situations where a scalar or vector alone is insufficient to describe how one vector is transformed into another. This note follows the approach of [*An Introduction to Tensors for Students of Physics and Engineering*](https://www.grc.nasa.gov/www/k-12/Numbers/Math/documents/Tensors_TM2002211716.pdf), grounding the formalism in concrete examples such as magnetic permeability and material stress.

## Core idea

The tensor hierarchy generalises scalars and vectors to objects with increasing directional complexity:

- Rank 0: scalars (1 component, magnitude only).
- Rank 1: vectors (3 components in 3D, magnitude and one direction).
- Rank 2: dyads/tensors (9 components in 3D, magnitude and two directions).
- Rank 3 and higher: triads and higher "n-ads" ($3^n$ components in 3D).

A rank-2 tensor is needed whenever a physical relation maps one vector to another, potentially changing both magnitude and direction.

## Physical motivation: permeability and stress

Two central examples motivate rank-2 tensors.

**Permeability tensor.** In anisotropic materials the magnetic flux density $\mathbf{B}$ and magnetic field $\mathbf{H}$ satisfy $\mathbf{B} = \boldsymbol{\mu} \cdot \mathbf{H}$, where $\boldsymbol{\mu}$ is a rank-2 tensor (not a scalar). This allows $\mathbf{B}$ to differ from $\mathbf{H}$ in both magnitude and direction.

**Stress tensor.** In continuum mechanics the force on a surface element is $d\mathbf{F} = \mathbf{T} \cdot d\mathbf{S}$, where $\mathbf{T}$ is the **stress tensor**. Stress must distinguish normal (tensile) and tangential (shear) components — a structure that cannot be captured by a single scalar or vector.

The general rule: the rank of the tensor needed reflects the complexity and directional structure of the physical quantity being modelled.

## Dyads, matrices, and tensor algebra

Tensor algebra is built from **dyads** — the outer product of two vectors.

- The dyad of two vectors $\mathbf{U}$, $\mathbf{V}$ is written $\mathbf{U}\mathbf{V}$ (neither dot nor cross product).
- In components, $\mathbf{U} = u_i \mathbf{e}_i$ and $\mathbf{V} = v_j \mathbf{e}_j$ give $\mathbf{U}\mathbf{V} = u_i v_j \, \mathbf{e}_i \mathbf{e}_j$, whose scalar coefficients $u_i v_j$ form a $3 \times 3$ matrix $\mu_{ij}$.
- Dyads are generally non-commutative: $\mathbf{U}\mathbf{V} \neq \mathbf{V}\mathbf{U}$, mirroring non-commutativity of matrix multiplication.

Key algebraic rules, valid for tensors of any rank:

- Product of a tensor with a scalar is commutative.
- Product of two tensors is generally not commutative.
- Rank of a product tensor is the sum of the factor ranks.
- Inner product of a vector with a vector reduces rank by 2 (e.g. $\mathbf{U} \cdot \mathbf{V}$ is a scalar).
- Inner product of tensors of ranks $m$ and $n$ gives a tensor of rank $m + n - 2$.

Rank-3 and higher tensors arise as triads and n-ads $\mathbf{U}\mathbf{V}\mathbf{W}\ldots$, with $3^n$ components in 3D.

## Contraction and extracting scalars/vectors

**Contraction** is the key operation for lowering tensor rank.

- Starting from an n-ad $\mathbf{U}\mathbf{V}\mathbf{W}\ldots\mathbf{A}\mathbf{B}\mathbf{C}$, inserting a dot between two adjacent vectors (e.g. $\mathbf{U} \cdot \mathbf{V}$) reduces rank by 2.
- Contracting a dyad $\mathbf{U}\mathbf{V}$ gives the scalar $\mathbf{U} \cdot \mathbf{V}$.
- Contracting a triad $\mathbf{U}\mathbf{V}\mathbf{W}$ can yield vectors like $(\mathbf{U} \cdot \mathbf{V})\mathbf{W}$ or $\mathbf{U}(\mathbf{V} \cdot \mathbf{W})$, which are generally different.

Contraction is a way to "read out" physical quantities from higher-rank tensor equations — for instance, power $\mathbf{F} \cdot \mathbf{V}$ from a force–velocity dyad.

## Coordinate transformations and tensor character

Tensors are defined by how their components transform between coordinate systems, reflecting the requirement that physical quantities be **coordinate-independent**.

- Scalars that are true rank-0 tensors satisfy $T = T^*$ for all frames (e.g. temperature at a point), while other scalars (e.g. Doppler-shifted frequency) do not transform trivially and are not tensors of rank 0.
- Vectors that are true rank-1 tensors must satisfy $\mathbf{V} = \mathbf{V}^*$ as geometric objects, even though their components differ between frames.
- The position vector (from the origin) is not a tensor, because it depends on the chosen origin; however, differences of position vectors and differentials $d\mathbf{V}$ are tensors.

For rank-2 tensors the standard component form is $B_s = \sum_t \mu_{st} H_t$, with implied summation over repeated indices (Einstein summation convention).

## Spaces, curvature, and coordinates

A conceptual digression connects tensors to the geometry of curved spaces, motivated by general relativity.

- Euclidean spaces (the line, the plane) have global metrics and standard coordinate systems (Cartesian, polar, etc.).
- Non-Euclidean spaces (the sphere, an egg-shaped surface) are curved, finite, and require **differential metrics** $ds^2 = g_{ij}\, dx^i\, dx^j$. Locally they appear Euclidean but globally have different geometry (e.g. no parallel lines on a sphere).

The central point: tensors live on these spaces as coordinate-independent objects, while different coordinate systems are just different descriptions of the same underlying geometry.

## Connections

- [[Some math]] — tensors as part of the mathematical backbone of physics
- [[Spaces and fields]] — field-theoretic context where tensors appear
- [[FLRW Metric]] — the metric tensor $g_{ij}$ in cosmology
- [[Quantum gravity]] — tensors on curved spacetime

## Sources

- [*An Introduction to Tensors for Students of Physics and Engineering*](https://www.grc.nasa.gov/www/k-12/Numbers/Math/documents/Tensors_TM2002211716.pdf) (NASA).

