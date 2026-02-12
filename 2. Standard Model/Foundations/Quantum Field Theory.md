# Quantum Field Theory

Quantum field theory (QFT) is the mathematical framework underlying the [[Standard model of particle physics|Standard Model]]. In QFT, every particle — electrons, quarks, photons, the Higgs — is an excitation of a corresponding quantum field that pervades all of spacetime.

## The core idea

Classical physics describes particles as point objects and fields (like the electromagnetic field) as smooth, continuous entities. Quantum mechanics makes particles wavelike. QFT goes further: it quantises the *fields themselves*, so that both matter and forces are described in the same language.

A quantum field $\hat{\phi}(x,t)$ is an operator at every point in spacetime. Its excitations — discrete energy packets — are what is observed as particles:
- An excitation of the electron field is an electron
- An excitation of the photon field is a photon
- An excitation of the Higgs field is a Higgs boson

Particle creation and annihilation are natural in this framework: exciting a field creates a particle, de-exciting it destroys one.

## Why QFT is necessary

Neither classical mechanics, nor ordinary quantum mechanics, nor classical field theory alone suffices for the Standard Model:

| Framework | Limitation |
|-----------|-----------|
| Classical mechanics | No quantum effects |
| Quantum mechanics | Fixed particle number; not relativistic |
| Classical field theory | No particle creation/annihilation; no quantum fluctuations |
| **QFT** | Combines quantum mechanics + special relativity + variable particle number |

Special relativity demands that energy can convert into mass ($E = mc^2$), meaning particle number is not conserved in high-energy processes. QFT handles this naturally.

## Key concepts

### The vacuum
The QFT vacuum is not empty — it is the lowest-energy state of all quantum fields. It still has **zero-point fluctuations**: virtual particle-antiparticle pairs constantly appearing and disappearing. These fluctuations have measurable consequences:
- The Lamb shift in hydrogen
- The Casimir effect between conducting plates
- The anomalous magnetic moment of the electron

The vacuum energy of quantum fields is also the origin of the [[Nature of Dark Energy|cosmological constant problem]] in cosmology.

### Feynman diagrams
Interactions in QFT are computed using **perturbation theory**, expanded in powers of the coupling constant. Each term is represented by a **Feynman diagram** — a pictorial shorthand for a precise mathematical integral. The rules for drawing diagrams are determined by [[The Lagrangian]].

### Renormalization
Naive QFT calculations often give infinite answers. **Renormalization** is the systematic procedure for absorbing these infinities into the definitions of physical quantities (masses, charges). A theory is **renormalizable** if only finitely many types of infinities appear — the Standard Model is renormalizable, which is one reason it works so well. See [[Gauge Couplings]] for how couplings "run" with energy.

### Spin-statistics connection
QFT combined with relativity proves a deep theorem:
- **Fermions** (half-integer spin: quarks, leptons) obey the Pauli exclusion principle — no two can occupy the same quantum state
- **Bosons** (integer spin: photon, gluons, W, Z, Higgs) can pile into the same state

This is not an assumption — it is a *consequence* of QFT.

## QFT and quantum mechanics

QFT extends the quantum mechanics described in [[Quantum mechanics|Quantum Mechanics]]:
- States still live in a Hilbert space, but it is now a **Fock space** — a direct sum of $n$-particle Hilbert spaces for all $n$
- Observables are still operators, but now they are built from the quantum fields
- Superposition, entanglement, and measurement all still apply

For the mathematical foundations (Hilbert spaces, operators, functional analysis), see [[Some math|Mathematical Foundations]].

## QFT in the Standard Model

The Standard Model is a specific QFT defined by:
1. The [[Gauge Symmetry]] group $SU(3)_C \times SU(2)_L \times U(1)_Y$
2. The matter content: [[Quarks]], [[Leptons]], [[Gauge Bosons]], [[Higgs Boson]]
3. [[The Lagrangian]], which encodes all interactions and dynamics

Everything else — cross sections, decay rates, particle masses, mixing angles — is calculated from this definition.

## Connections

-[[Standard model of particle physics]]] — QFT as the foundational framework
- [[Gauge Symmetry]] — determines the interactions in the QFT
- [[The Lagrangian]] — defines the specific QFT of the Standard Model
- [[Quantum mechanics|Quantum Mechanics]] — QFT extends QM to relativistic, variable-particle-number settings
- [[Some math|Mathematical Foundations]] — Hilbert spaces, operators, functional analysis
- [[9. Notes/Quantum gravity|Cosmology and Quantum Gravity]] — QFT on curved spacetime bridges to cosmology
