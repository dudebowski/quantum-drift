# Flavor Mixing

Flavor mixing describes the fact that the **mass eigenstates** of quarks and leptons are not the same as their **weak interaction eigenstates**. This mismatch, encoded in the CKM and PMNS matrices, is the origin of flavor-changing processes and CP violation in the [[Standard model of particle physics|Standard Model]].

## Why mixing occurs

In [[The Lagrangian]], the Yukawa couplings form **matrices** in generation space (3×3 for three generations of [[Quarks]] or [[Leptons]]). After the [[Higgs Mechanism]] gives fermions their masses, diagonalising these Yukawa matrices to find the mass eigenstates requires separate rotations of the left-handed up-type and down-type fields. These rotations do not, in general, coincide — the mismatch is the **mixing matrix**.

## The CKM matrix (quarks)

The **Cabibbo-Kobayashi-Maskawa** matrix relates the weak eigenstates ($d'$, $s'$, $b'$) to the mass eigenstates ($d$, $s$, $b$):

$$\begin{pmatrix} d' \\ s' \\ b' \end{pmatrix} = V_{\text{CKM}} \begin{pmatrix} d \\ s \\ b \end{pmatrix}$$

When a $W^\pm$ boson mediates a quark transition, the amplitude for $u_i \to d_j + W^+$ is proportional to $|V_{ij}|$.

### Structure

$$|V_{\text{CKM}}| \approx \begin{pmatrix} 0.974 & 0.225 & 0.004 \\ 0.225 & 0.973 & 0.041 \\ 0.009 & 0.040 & 0.999 \end{pmatrix}$$

Key features:
- Nearly diagonal — transitions within the same generation dominate
- Off-diagonal elements decrease with generation gap (Cabibbo suppression)
- The Wolfenstein parameterisation organises this as an expansion in $\lambda \approx 0.225$

### Parameters
A 3×3 unitary matrix has 4 independent physical parameters:
- **3 mixing angles** ($\theta_{12}$, $\theta_{13}$, $\theta_{23}$)
- **1 CP-violating phase** ($\delta$)

The CP phase makes the CKM matrix complex and is the **sole source of CP violation** in the quark sector of the Standard Model. See [[Weak Force]].

### CP violation
The complex phase leads to differences between matter and antimatter processes:
- Observed in kaon, $B$-meson, and $D$-meson systems
- Quantified by the Jarlskog invariant: $J \approx 3 \times 10^{-5}$
- Necessary (but in the SM, insufficient) for explaining the [[Baryon Asymmetry]]

## The PMNS matrix (leptons)

The **Pontecorvo-Maki-Nakagawa-Sakata** matrix plays the same role for neutrinos:

$$\begin{pmatrix} \nu_e \\ \nu_\mu \\ \nu_\tau \end{pmatrix} = U_{\text{PMNS}} \begin{pmatrix} \nu_1 \\ \nu_2 \\ \nu_3 \end{pmatrix}$$

where $\nu_1, \nu_2, \nu_3$ are the mass eigenstates.

### Structure

Unlike the CKM matrix, the PMNS matrix has **large mixing angles**:

| Parameter | Approximate value |
|-----------|------------------|
| $\theta_{12}$ (solar) | ~34° |
| $\theta_{23}$ (atmospheric) | ~45° |
| $\theta_{13}$ (reactor) | ~8.5° |
| $\delta_{\text{CP}}$ | Under measurement (~200°?) |

The large angles mean neutrino flavor conversion is dramatic — a $\nu_\mu$ produced in a pion decay has a substantial probability of arriving as a $\nu_\tau$ at a distant detector.

### Parameters
For Dirac neutrinos: 3 angles + 1 CP phase (same as CKM).
For Majorana neutrinos: 3 angles + 3 CP phases (2 extra "Majorana phases" that do not affect oscillations but matter for neutrinoless double beta decay). See [[Neutrino Masses]].

## Why CKM ≠ PMNS

The CKM matrix is nearly diagonal (small mixing); the PMNS matrix has large mixing angles. The Standard Model does not explain this contrast — both are free parameters. Understanding the pattern of mixing angles and CP phases across quarks and leptons is a major goal of flavor physics.

## How mixing is measured

- **CKM**: $B$-factory experiments (Belle, BaBar, LHCb), kaon experiments, precision unitarity tests
- **PMNS**: Solar neutrino experiments (SNO, Super-K), atmospheric neutrinos, reactor experiments (Daya Bay, RENO, JUNO), accelerator experiments (T2K, NOvA, DUNE)

## Connections

- [[Standard model of particle physics]] — CKM and PMNS as parameters
- [[The Lagrangian]] — mixing arises from the Yukawa matrices
- [[Fermion Masses]] — diagonalising the mass matrices generates mixing
- [[Weak Force]] — $W^\pm$ interactions are where mixing manifests
- [[Quarks]] — CKM mixing governs quark flavor transitions
- [[Leptons]] — PMNS mixing governs neutrino oscillations
- [[Neutrino Masses]] — the PMNS matrix requires nonzero neutrino masses
- [[Baryon Asymmetry]] — CP violation from mixing is necessary for baryogenesis
