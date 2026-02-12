# The Hubble Constant

The Hubble constant $H_0$ is the present-day expansion rate of the universe. It is one of the most important parameters of the [[Standard model of cosmology|ΛCDM model]], setting the overall scale of cosmic distances, ages, and densities.

## Definition

The Hubble parameter $H(t)$ is defined as:

$$H(t) = \frac{\dot{a}(t)}{a(t)}$$

where $a(t)$ is the scale factor from the [[FLRW Metric]]. The Hubble constant $H_0$ is simply its value today:

$$H_0 = H(t_0)$$

It is conventionally quoted in units of $\text{km/s/Mpc}$, meaning: for every megaparsec of distance, galaxies recede $H_0$ km/s faster. This is **Hubble's law**:

$$v = H_0 \, d$$

## What $H_0$ determines

- **Age of the universe**: $t_0 \approx 1/H_0$ (modulo the detailed expansion history). For $H_0 \approx 70$, this gives $t_0 \approx 13.8$ billion years.
- **Critical density**: $\rho_{\text{crit}} = 3H_0^2 / (8\pi G)$, the density that gives a spatially flat universe. All [[Density Parameters]] are defined relative to $\rho_{\text{crit}}$.
- **Observable universe size**: the comoving distance to the particle horizon depends on $H_0$ and the other $\Omega$ parameters.
- **Physical distances**: converting redshift to distance requires $H_0$.

## How it is measured

### Early-universe (indirect)
The [[Cosmic Microwave Background]] power spectrum, combined with the ΛCDM model, predicts $H_0$ as a derived parameter:

$$H_0 = 67.4 \pm 0.5\,\text{km/s/Mpc} \quad (\text{Planck 2018})$$

This is an *inferred* value — it depends on the assumption that ΛCDM is correct.

### Late-universe (direct)
The **cosmic distance ladder** measures $H_0$ directly, step by step:
1. **Geometric distances**: parallax to nearby Cepheid variable stars
2. **Cepheid period-luminosity relation**: calibrates distances to galaxies hosting Type Ia supernovae
3. **[[Type Ia Supernovae]]**: extend the distance scale to cosmological redshifts

The SH0ES team finds:

$$H_0 = 73.0 \pm 1.0\,\text{km/s/Mpc} \quad (\text{Riess et al. 2022})$$

### Other methods
- **Tip of the red giant branch (TRGB)**: an alternative distance indicator, giving $H_0 \approx 69.8$
- **Gravitational wave sirens**: binary neutron star mergers provide a distance measurement independent of the electromagnetic distance ladder
- **Time-delay cosmography**: strongly lensed quasars give $H_0 \approx 73$
- **BAO + BBN**: baryon acoustic oscillations calibrated with BBN baryon density give $H_0 \approx 67–68$

## The Hubble tension

The ~5σ discrepancy between the CMB/early-universe value (~67.4) and the distance-ladder/late-universe value (~73.0) is the **Hubble tension** — one of the most significant open problems in cosmology. See [[Hubble Tension]] for details.

## Connections

- [[FLRW Metric]] — $H_0 = \dot{a}/a$ at the present epoch
- [[Friedmann Equations]] — $H_0$ enters the energy constraint equation
- [[Density Parameters]] — all $\Omega$ values are defined relative to $\rho_{\text{crit}}(H_0)$
- [[Type Ia Supernovae]] — calibrate the local $H_0$
- [[Cosmic Microwave Background]] — provides the early-universe $H_0$
- [[Hubble Tension]] — the discrepancy between early and late measurements
