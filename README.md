# Quantum Drift

Physics currently rests on two pillars — the **Standard Model of particle physics** (the very small) and the **ΛCDM standard model of cosmology** (the very large). Both are spectacularly successful, yet they don't talk to each other. This repository explores both models, the mathematics behind them, and the open frontiers where they might connect.

## The Two Standard Models

### The Standard Model of Particle Physics

The Standard Model is an $SU(3) \times SU(2) \times U(1)$ gauge theory that describes all known elementary particles and three of the four fundamental forces — the strong, weak, and electromagnetic interactions. Its predictions have been confirmed to extraordinary precision across decades of experiments.

The full Lagrangian that encodes the entire theory:

$$\mathcal{L}_{\text{SM}} = -\frac{1}{4}G^a_{\mu\nu}G^{a\mu\nu} - \frac{1}{4}W^i_{\mu\nu}W^{i\mu\nu} - \frac{1}{4}B_{\mu\nu}B^{\mu\nu} + \sum_f \bar{\psi}_f \, i \gamma^\mu D_\mu \, \psi_f + (D_\mu \Phi)^\dagger (D^\mu \Phi) - V(\Phi) - y_u \bar{Q}_L \tilde{\Phi} u_R - y_d \bar{Q}_L \Phi d_R - y_e \bar{L}_L \Phi e_R + \text{h.c.}$$

This single expression encodes every particle, interaction, and prediction of the Standard Model.

### The Standard Model of Cosmology (ΛCDM)

The ΛCDM model describes an expanding universe composed of roughly 69% dark energy, 26% dark matter, and 5% ordinary baryonic matter. It is built on general relativity and anchored by decades of precision observations.

The FLRW Metric that underpins this model:

$$ds^2 = -c^2\,dt^2 + a(t)^2 \left[\frac{dr^2}{1 - kr^2} + r^2\left(d\theta^2 + \sin^2\theta\,d\phi^2\right)\right]$$

This geometry, combined with Einstein's field equations, describes the expansion of the entire universe.

## Prerequisites

To follow the material in this vault you should be comfortable with:

- **Calculus** — derivatives, integrals, differential equations
- **Linear algebra** — vectors, matrices, eigenvalues
- **Classical mechanics** — Lagrangian/Hamiltonian formulation is helpful
- **Quantum mechanics** — superposition, wave functions, operators, measurement
- **Special & general relativity** — spacetime, Lorentz transformations, basic ideas of curved spacetime

More advanced topics (tensors, Lie algebras, differential geometry) are introduced as needed.

## How to use this vault

1. Install [Obsidian](https://obsidian.md)
2. Open this folder as a vault (File → Open folder as vault)
3. Navigate via internal links

## About this vault

This Obsidian vault is a guide for building foundational understanding of these two standard models and exploring what lies beyond them. Content will grow and evolve as new topics and connections are added.
