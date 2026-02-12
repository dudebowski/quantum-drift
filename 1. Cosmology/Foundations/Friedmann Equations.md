# The Friedmann Equations

The Friedmann equations are the dynamical heart of the [[Standard model of cosmology|ΛCDM model]]. They are derived by inserting the [[FLRW Metric]] into Einstein's field equations of general relativity, and they govern how the scale factor $a(t)$ evolves in time given the energy content of the universe.

## The equations

### First Friedmann equation (energy constraint)

$$H^2 \equiv \left(\frac{\dot{a}}{a}\right)^2 = \frac{8\pi G}{3}\,\rho - \frac{kc^2}{a^2} + \frac{\Lambda c^2}{3}$$

This relates the **expansion rate** $H$ to:
- $\rho$ — total energy density (matter + radiation)
- $k$ — spatial curvature
- $\Lambda$ — the cosmological constant (dark energy)

### Second Friedmann equation (acceleration equation)

$$\frac{\ddot{a}}{a} = -\frac{4\pi G}{3}\left(\rho + \frac{3p}{c^2}\right) + \frac{\Lambda c^2}{3}$$

This tells us whether the expansion is **accelerating** or **decelerating**, depending on the balance between:
- $\rho + 3p/c^2$ — the gravitational pull of energy and pressure (slows expansion)
- $\Lambda$ — the cosmological constant (drives acceleration)

### Fluid equation (energy conservation)

$$\dot{\rho} + 3H\left(\rho + \frac{p}{c^2}\right) = 0$$

This is not independent — it follows from the other two — but is useful for tracking how energy density dilutes as the universe expands.

## Equations of state

Different components of the universe have different **equations of state** $p = w\rho c^2$, which determine how their densities evolve:

| Component | $w$ | Density scales as |
|-----------|-----|-------------------|
| Radiation | $1/3$ | $\rho \propto a^{-4}$ |
| Matter (dust) | $0$ | $\rho \propto a^{-3}$ |
| Cosmological constant | $-1$ | $\rho = \text{const}$ |

This means:
- **Radiation** dominated the early universe (dilutes fastest)
- **Matter** dominated the middle epoch
- **Dark energy** ($\Lambda$) dominates today and drives accelerated expansion

## The density parameter $\Omega$

It is conventional to rewrite the first Friedmann equation using dimensionless density parameters:

$$\Omega_r + \Omega_m + \Omega_\Lambda + \Omega_k = 1$$

where $\Omega_i = \rho_i / \rho_{\text{crit}}$ and $\rho_{\text{crit}} = 3H^2 / (8\pi G)$. The measured values are approximately $\Omega_m \approx 0.31$, $\Omega_\Lambda \approx 0.69$, and $\Omega_k \approx 0$ (flat universe). See [[Density Parameters]] for details.

## Connections

- [[FLRW Metric]] — the geometry from which these equations are derived
- [[Hubble Constant]] — $H_0$ is the present-day value of $H$
- [[Density Parameters]] — the $\Omega$ values that parameterise the Friedmann equations
- [[Dark Energy]] — the $\Lambda$ term driving late-time acceleration
- [[Cosmic Inflation]] — the Friedmann equations with an inflaton field driving exponential expansion
