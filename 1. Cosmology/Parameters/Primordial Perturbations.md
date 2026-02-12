# Primordial Perturbations

The primordial perturbations are the tiny initial density fluctuations that seeded all the structure in the universe — from the anisotropies in the [[Cosmic Microwave Background]] to the [[Large-Scale Structure|cosmic web of galaxies]]. In the [[Standard model of cosmology|ΛCDM model]], these perturbations are characterised by just two numbers: an amplitude $A_s$ and a spectral index $n_s$.

## Origin: quantum fluctuations during inflation

During [[Cosmic Inflation]], quantum vacuum fluctuations of the inflaton field were stretched to macroscopic (and then cosmological) scales by the exponential expansion. When inflation ended, these became classical density perturbations — tiny over- and under-densities in the matter-radiation fluid.

This is a striking prediction: the largest structures in the universe grew from quantum fluctuations.

## The primordial power spectrum

The statistical properties of the perturbations are encoded in the **primordial power spectrum** $\mathcal{P}(k)$, giving the variance of fluctuations as a function of wavenumber $k$ (spatial scale):

$$\mathcal{P}(k) = A_s \left(\frac{k}{k_*}\right)^{n_s - 1}$$

where:
- $A_s$ is the **scalar amplitude** — the overall normalisation of fluctuations, evaluated at a pivot scale $k_* = 0.05\,\text{Mpc}^{-1}$
- $n_s$ is the **scalar spectral index** — it describes the tilt of the spectrum

### Key values (Planck 2018)

| Parameter | Value | Meaning |
|-----------|-------|---------|
| $A_s$ | $(2.10 \pm 0.03) \times 10^{-9}$ | Perturbations are very small (~$10^{-5}$) |
| $n_s$ | $0.965 \pm 0.004$ | Slightly less power on small scales than large scales |

### What $n_s$ tells us
- $n_s = 1$ would mean exactly scale-invariant (the Harrison-Zel'dovich spectrum)
- $n_s < 1$ (as observed) means slightly more power at large scales — a generic prediction of slow-roll inflation
- The measured value $n_s \approx 0.965$ rules out exact scale invariance at >5σ, providing evidence for inflation

## Other perturbation parameters

### Optical depth to reionization $\tau$
When the first stars and galaxies formed ($z \sim 6$–$10$), they reionised the intergalactic hydrogen. Free electrons scatter CMB photons, slightly damping the small-scale anisotropies and producing large-scale polarisation. The optical depth $\tau \approx 0.054$ measures the total amount of this rescattering.

$\tau$ is degenerate with $A_s$ in the temperature power spectrum (both affect the overall amplitude), so polarisation data is needed to break the degeneracy.

### Tensor-to-scalar ratio $r$
Inflation also predicts primordial **gravitational waves** (tensor perturbations). The ratio $r$ of their power to the scalar perturbation power is related to the energy scale of inflation:

$$V^{1/4}_{\text{inflation}} \propto r^{1/4}$$

Current upper limit: $r < 0.036$ (BICEP/Keck 2021). A detection would pin down the inflation energy scale and generate B-mode polarisation in the CMB. See [[Cosmic Microwave Background]].

### Running of the spectral index
The spectral index itself may vary slowly with scale: $dn_s / d\ln k$. Current data is consistent with zero running, but future experiments could detect it.

## Gaussianity

Simple inflation models predict the perturbations are very nearly **Gaussian** — their statistics are fully described by the power spectrum. Non-Gaussianity (measured by the parameter $f_{\text{NL}}$) would signal more complex inflationary dynamics or multiple fields. Planck finds $f_{\text{NL}}$ consistent with zero.

## Connections

- [[Cosmic Inflation]] — the mechanism that generates primordial perturbations
- [[Cosmic Microwave Background]] — where the perturbation spectrum is most precisely measured
- [[Large-Scale Structure]] — perturbations grow into the galaxy distribution
- [[Density Parameters]] — the $\Omega$ values determine how perturbations evolve after inflation
- [[Hubble Constant]] — enters the mapping between $k$ and observed angular scales
