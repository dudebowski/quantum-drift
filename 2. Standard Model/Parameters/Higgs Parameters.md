# Higgs Parameters

The Higgs sector of the [[Standard model of particle physics|Standard Model]] is described by a small number of parameters that control the shape of the Higgs potential, the scale of electroweak symmetry breaking, and the mass of the [[Higgs Boson]].

## The parameters

### Vacuum expectation value (VEV)

$$v = \frac{1}{\sqrt{\sqrt{2}\,G_F}} \approx 246\,\text{GeV}$$

The VEV is the value of the Higgs field in the vacuum after [[Higgs Mechanism|electroweak symmetry breaking]]. It sets the **electroweak scale** and is the single most important mass scale in the Standard Model:
- $W$ and $Z$ masses: $m_W = gv/2$, $m_Z = \sqrt{g^2+g'^2}\,v/2$
- All fermion masses: $m_f = y_f v / \sqrt{2}$

It is measured extremely precisely through the Fermi constant $G_F$ from muon decay.

### Higgs boson mass

$$m_H = \sqrt{2\lambda}\,v \approx 125.25 \pm 0.17\,\text{GeV}$$

The mass is determined by both the VEV and the quartic self-coupling $\lambda$. The measured value gives:

$$\lambda \approx 0.13$$

### The Higgs potential

The potential is:

$$V(\Phi) = -\mu^2 \Phi^\dagger \Phi + \lambda (\Phi^\dagger \Phi)^2$$

with two parameters:
- $\mu^2 > 0$: triggers symmetry breaking (determines the VEV via $v^2 = \mu^2/\lambda$)
- $\lambda > 0$: the quartic self-coupling (determines the Higgs mass via $m_H^2 = 2\lambda v^2$)

Equivalently, the two physical parameters are $(v, m_H)$ or $(\mu, \lambda)$ — measuring any two determines the rest.

## The Higgs self-coupling

The Higgs potential predicts that the Higgs boson interacts with itself. The trilinear self-coupling is:

$$\lambda_{HHH} = \frac{3m_H^2}{v} \approx 190\,\text{GeV}$$

Measuring this coupling requires producing **two Higgs bosons** simultaneously ($pp \to HH$), which is extremely rare. It is a primary target of the HL-LHC (expected to run through the 2030s) and proposed future colliders (FCC-hh, CLIC).

A measured value deviating from the SM prediction would indicate new physics in the Higgs potential — for instance, additional scalar fields or a modified symmetry-breaking sector.

## Vacuum stability

The quartic coupling $\lambda$ also runs with energy scale (via the renormalization group). Due to the large top-quark Yukawa coupling, $\lambda$ decreases at high energies and may turn negative at scales around $10^{10}$–$10^{12}$ GeV. If $\lambda < 0$, the Higgs potential becomes unbounded from below — the electroweak vacuum would be **metastable**.

Current best measurements of $m_H$ and $m_t$ place the SM just inside the metastable region. The vacuum lifetime is vastly longer than the age of the universe, so there is no practical danger, but this curious situation raises deep questions about the UV completion of the Standard Model.

## What the Higgs parameters don't explain

- **Why $v \approx 246$ GeV?** The VEV is many orders of magnitude below the Planck scale ($10^{19}$ GeV). Explaining this hierarchy is the [[Hierarchy Problem]].
- **Why is $m_H \approx 125$ GeV?** In the SM, the Higgs mass receives quadratically divergent quantum corrections that would naturally push it to the cutoff scale. Keeping it at 125 GeV requires either fine-tuning or new physics (SUSY, composite Higgs, etc.).
- **Is this the minimal Higgs sector?** Extended models (two-Higgs-doublet models, singlet extensions, SUSY Higgs sectors) predict additional scalar particles.

## Connections

- [[Standard model of particle physics]] — Higgs parameters as part of the parameterization
- [[Higgs Mechanism]] — the VEV and potential drive symmetry breaking
- [[Higgs Boson]] — the physical particle with mass $m_H$
- [[The Lagrangian]] — $\mathcal{L}_{\text{Higgs}}$ contains the potential
- [[Fermion Masses]] — proportional to $v$ via Yukawa couplings
- [[Gauge Couplings]] — $W/Z$ masses relate $v$ to gauge couplings
- [[Hierarchy Problem]] — why is $v$ so much smaller than the Planck scale?
