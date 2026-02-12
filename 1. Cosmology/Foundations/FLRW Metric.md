# The FLRW Metric

The Friedmann–Lemaître–Robertson–Walker (FLRW) metric is the exact solution of general relativity that describes a homogeneous, isotropic, expanding (or contracting) universe. It is the geometric backbone of the [[Standard model of cosmology|ΛCDM model]].

## The metric

In comoving coordinates, the FLRW line element is:

$$ds^2 = -c^2\,dt^2 + a(t)^2 \left[\frac{dr^2}{1 - kr^2} + r^2\left(d\theta^2 + \sin^2\theta\,d\phi^2\right)\right]$$

where:
- $a(t)$ is the **scale factor**, encoding how distances between comoving observers change with time
- $k$ is the **spatial curvature**: $k = +1$ (closed/spherical), $k = 0$ (flat), $k = -1$ (open/hyperbolic)
- $(r, \theta, \phi)$ are comoving spatial coordinates — they label points that move with the expansion

## Key ideas

### Scale factor $a(t)$
- At the present time $t_0$, the scale factor is conventionally set to $a(t_0) = 1$.
- The **cosmological redshift** of light from a distant source is directly related to the scale factor: $1 + z = a(t_0)/a(t_{\text{emit}})$.
- All cosmic distances scale with $a(t)$: if the universe doubles in size, $a$ doubles.

### Spatial curvature $k$
- Observations (especially the CMB) strongly indicate $k \approx 0$, meaning the universe is spatially flat or very nearly so.
- For $k = 0$ the spatial part simplifies to ordinary flat 3D space in expanding coordinates.

### Comoving vs proper distance
- **Comoving distance** factors out the expansion: it stays constant for objects moving only with the Hubble flow.
- **Proper distance** $d_{\text{proper}} = a(t) \times d_{\text{comoving}}$ gives the physical distance at time $t$.

## How it connects to dynamics

The FLRW metric itself is pure geometry — it says nothing about *why* the universe expands. That comes from plugging this metric into Einstein's field equations, which yields the [[Friedmann Equations]]. Those equations relate $a(t)$, $k$, and the energy content of the universe.

## Mathematical context

The FLRW metric is a special case of a Lorentzian manifold — a 4-dimensional spacetime with signature $(-,+,+,+)$. The assumption of homogeneity and isotropy (the [[Cosmological Principle]]) restricts the spatial part to one of three maximally symmetric geometries (sphere, flat, hyperboloid), leaving only $a(t)$ and $k$ as free parameters.

For the differential geometry background, see [[Some math|Mathematical Foundations]].

## Connections

- [[Cosmological Principle]] — the symmetry assumption that leads to FLRW
- [[Friedmann Equations]] — the dynamical equations derived from FLRW + Einstein's equations
- [[Hubble Constant]] — $H_0 = \dot{a}/a$ evaluated today
- [[Cosmic Inflation]] — drives $a(t)$ through a phase of exponential growth in the early universe
