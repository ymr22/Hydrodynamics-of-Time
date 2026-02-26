# The Hydrodynamics of Time: Phase Friction, Kinematic Drag, and the Arrow of Time

**Author:** Yağmur Üstel
**Hardware:** IBM Quantum `ibm_torino` (156-Qubit Heron Processor)

### 🌌 Overview

This repository contains the experimental data and code for the paper *"The Hydrodynamics of Time: Phase Friction, Kinematic Drag, and the Arrow of Time in a Discrete Superfluid Vacuum"*.

We demonstrate that Time is not a geometric dimension, but a hydrodynamic observable: the continuous phase evolution of a Discrete Topological Superfluid. By mapping relativistic and thermodynamic parameters onto a superconducting qubit lattice, we simulated the mechanical flow of time and resolved five major temporal paradoxes.

### 🧪 The Experiments

Click on the notebooks below to view the simulation code and results:

**1. Kinematic Time Dilation (Twin Paradox)**

* **Result:** We detected severe phase retardation in moving frames. The computational drag of translating a topological defect across the lattice via `SWAP` operations consumed phase capacity, mechanically deriving Special Relativity without Minkowski geometry.

**2. Gravitational Phase Shift (Pound-Rebka)**

* **Result:** We identified that a gravity well is a gradient of Topological Viscosity. Spectral FFT analysis of a phonon falling into the density well confirmed a mechanical acoustic blueshift ($+\Delta\omega$), replacing spacetime curvature with standard fluid optics.

**3. The Arrow of Time (Entropic Decoherence)**

* **Result:** We mapped the Shannon entropy of a macroscopic 7-node GHZ state. The irreversible climb from an initial 3.1 bits up to >5.0 bits confirms that the unidirectional flow of time is driven by the dissipation of phase information into the viscous vacuum.

**4. Causality Protection (Closed Timelike Curves)**

* **Result:** We discovered a strict mechanical limit to time travel. Injecting a retrocausal phase current ($-\omega t$) resulted in destructive interference and dielectric breakdown, collapsing the state survival probability to ~0.5 (a maximally mixed state) and naturally preserving causality.

**5. Topological Impedance (Elitzur-Vaidman Bomb Tester)**

* **Result:** We successfully reproduced interaction-free measurement. A "live bomb" acts as a region of infinite mechanical impedance, yielding a ~25% paradox detection rate as the vacuum's static tension field maps the blockage and reroutes kinetic flow via the principle of least action.

### ⚙️ How to Reproduce

1. Install requirements: `pip install qiskit qiskit-ibm-runtime numpy matplotlib scipy`
2. Open any `.ipynb` file in Jupyter or VS Code.
3. Insert your IBM Quantum Token.
4. Run the cells to simulate the hydrodynamics of time.

### License

MIT License