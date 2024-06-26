# Quantum Chemistry with Energy Transformers Networks

Quantum neural networks have been shown to deliver exceptional performance as surrogate models for problems in many-body quantum systems. To predict electronic wavefunctions, this repo brings together the [energy transformer architect](https://github.com/bhoov/energy-transformer-jax/tree/main) with transformer methods from [Psiformer](https://arxiv.org/pdf/2211.13672.pdf) introduced by Deepmind.

<!-- 
- [ ] Input: Molecular data
- [ ] Features: Electron-Nuclear, Electron-Electron &rarr; Ansatz
- [ ] Dense Associative block (DAB): Electron-Nuclear &rarr; Basic WF &rarr; Match Memory &rarr; WF
  - Learns configuration with greater number and tuned terms
  - Configurations/memories are preloaded, and possibly updated to match changing basis set. Look at computational costs of Det calc. vs Energy calc.
- [ ] Attenion block (AB): Electron-Electron &rarr; Projection in basis chosen by 1) DAB 2) AO expanded 3) MO from AO
  - Learns electron-electron interaction
- [ ] &Sigma; (Ansatz, WF-DAB, WF-AB)
- [ ] Minimize energy of system according to DAB and Psiformer like loss
  

After verifying chemical accuracy in free system 
use model to then study perturbed and strongly coupled
systems. Cavity QED, periodic systems, easy system with measurable
features - phase from magnetic field...
-->
