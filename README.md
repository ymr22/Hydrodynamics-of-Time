# The Hydrodynamics of Time: Phase Friction, Kinematic Drag, and the Arrow of Time

**Author:** Yağmur Üstel  
**Theory:** The Quantum Loom / Discrete Topological Superfluid (DTS)  
**Hardware:** IBM Quantum `ibm_torino` (133-Qubit Heron Processor)

---

### 🌌 Overview

This repository contains the experimental data and code for the paper **"The Hydrodynamics of Time: Phase Friction, Kinematic Drag, and the Arrow of Time in a Discrete Superfluid Vacuum."**

Contrary to the geometric interpretation of General Relativity, this research demonstrates that Time is a **hydrodynamic observable**: the continuous phase evolution of a Discrete Topological Superfluid. By mapping relativistic and thermodynamic parameters onto a superconducting qubit lattice, we simulated the mechanical flow of time and resolved five major temporal paradoxes.

---

### 🧪 The Experiments

Explore the individual research modules below. Each notebook contains the theoretical background, the Qiskit circuit implementation, and the hardware results. 

*Note: Physical hardware paths are hardcoded to match the `ibm_torino` execution data published in the paper to ensure reproducibility while protecting proprietary mapping algorithms (Patent Pending).*

#### 1. [Kinematic Time Dilation (Twin Paradox)](./01_kinematic_twin_paradox.ipynb)
* **The Paradox:** Why do moving clocks slow down?
* **DTS Resolution:** Phase retardation in moving frames is a result of **Kinematic Drag**.
* **Result:** Computational translation via `SWAP` gates consumes the lattice's phase capacity, mechanically deriving the Lorentz factor without Minkowski geometry.

#### 2. [Gravitational Phase Shift (Pound-Rebka)](./02_gravitational_pound_rebka.ipynb)
* **The Paradox:** Why does light shift frequency in a gravity well?
* **DTS Resolution:** Gravity is a gradient of **Topological Viscosity**.
* **Result:** Spectral FFT analysis of a phonon falling into the density well confirmed a mechanical acoustic blueshift ($+\Delta\omega$), replacing spacetime curvature with fluid optics.

#### 3. [The Arrow of Time (Entropic Decoherence)](./03_arrow_of_time.ipynb)
* **The Paradox:** Why does time only flow forward?
* **DTS Resolution:** Irreversibility is the **dissipation of phase information** into the viscous vacuum.
* **Result:** Measurement of the Shannon entropy of a 7-node GHZ state shows an irreversible climb toward maximum entropy, proving the Arrow of Time is a thermodynamic expansion into vacuum degrees of freedom.

#### 4. [Causality Protection (Closed Timelike Curves)](./04_causality_protection.ipynb)
* **The Paradox:** Can we travel back in time to change the past?
* **DTS Resolution:** Time travel is limited by **Mechanical Impedance** and destructive interference.
* **Result:** Injecting a retrocausal phase current ($-\omega t$) caused a state collapse to $P \approx 0.5$, demonstrating that the vacuum naturally "jams" to prevent logical paradoxes.

---

### ⚙️ Reproduction & Setup

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/your-username/hydrodynamics-of-time.git](https://github.com/your-username/hydrodynamics-of-time.git)
    cd hydrodynamics-of-time
    ```

2.  **Install Dependencies:**
    ```bash
    pip install qiskit qiskit-ibm-runtime numpy matplotlib scipy
    ```

3.  **Run the Notebooks:**
    * Open any `.ipynb` file in the `notebooks/` directory.
    * Provide your IBM Quantum API Token when prompted.
    * Ensure the backend is set to `service.backend('ibm_torino')` to match the hardcoded qubit layouts.

---

### 📜 Citation

If you use this code or theory in your research, please cite the foundational paper:

> Üstel, Y. (2025). *The Hydrodynamics of Time: Phase Friction, Kinematic Drag, and the Arrow of Time in a Discrete Superfluid Vacuum*. Zenodo. DOI: 10.5281/zenodo.XXXXXXX

### License
MIT License
