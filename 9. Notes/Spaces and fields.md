Think of “space + geometry + fields” as three layers that build on each other.

## 1. Manifolds: what “space” really is

A **manifold** is a space that, if you zoom in enough, looks like ordinary flat space $\mathbb{R}^n$, even if globally it is curved or has holes.

- The surface of a sphere is a 2D manifold: locally it looks like a flat plane, globally it wraps around.
    
- A torus (doughnut shape) is another 2D manifold: locally flat, globally has a hole.
    

Instead of one global coordinate system, you cover the manifold with overlapping “maps” (charts), each with its own coordinates, and make sure the overlaps are smoothly compatible. This is what lets you do calculus (derivatives, integrals) on curved spaces just like in $\mathbb{R}^n$.

## 2. Geometry on a manifold: measuring things

A bare manifold only tells you what is “near what”; it doesn’t yet know about distances or angles. For that you add extra structure, typically a **metric**.

- A metric tells you the length of a small displacement, the angle between directions, the length of curves.
    
- With a metric, you can talk about shortest paths (geodesics) and curvature.
    

Curvature measures how much the space deviates from flatness.

- On a plane, triangles have angles adding to $180^\circ$.
    
- On a sphere, triangle angles add to more than $180^\circ$, which reflects positive curvature.
    

In general relativity, spacetime is a 4D manifold with a special kind of metric (Lorentzian), and curvature of this spacetime encodes gravity.

## 3. Bundles: extra stuff attached to each point

Often, at every point of your manifold, you want to attach some extra “internal space”. The clean way to do this is a **bundle**.

- Example: at each point on a surface you have a tangent plane; all these planes together form the **tangent bundle**.
    
- More generally, a **vector bundle** attaches a vector space to each point (these could be copies of $\mathbb{R}^n$, $\mathbb{C}^n$, spinor spaces, etc.).
    

A bundle “looks locally like” (base space) × (fiber), but globally it can be twisted. This twisting is where topology shows up in physics (monopoles, topological phases, etc.).

## 4. Fields: something living over space

A **field** is simply a rule that, to each point of spacetime (the base manifold), assigns some value in the fiber above it. In other words, a field is a **section of a bundle**.

- Scalar field: assigns a number to each point (section of a trivial line bundle).
    
- Vector field: assigns a vector in the tangent space at each point (section of the tangent bundle).
    
- Spinor field: assigns a spinor at each point (section of a spinor bundle).
    
Gauge fields (like the electromagnetic potential, or non‑abelian gauge fields in the Standard Model) are slightly more subtle: mathematically they are **connections** on principal bundles, but you can still think of them as defining how fields “twist” as you move along the manifold.

## 5. The big picture

Putting it together:

- The **arena** is a manifold with geometry (metric, sometimes also a connection chosen in the tangent bundle).
    
- The **players** are fields, which are sections of various bundles over that manifold.
    
- The **rules of interaction** (Lagrangians, equations of motion) tell you how the geometry affects the fields (e.g., curvature enters the equations) and, in turn, how the fields can back‑react on the geometry (like matter curves spacetime in GR).

## Connections

- [[Some math]] — the mathematical tools for manifolds and geometry
- [[Tensors]] — tensor fields on manifolds
- [[FLRW Metric]] — a specific metric on a cosmological manifold
- [[Gauge Symmetry]] — gauge fields as connections on principal bundles
- [[Quantum Field Theory]] — fields as sections of bundles over spacetime