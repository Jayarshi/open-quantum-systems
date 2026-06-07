# Open Quantum Systems

A collection of analytical and numerical demonstrations for open quantum system dynamics. The repository focuses on exact models, non-Markovian dynamics, and modern numerical approaches used to describe quantum systems interacting with structured environments.

The notebooks are intended for graduate students, researchers, and practitioners working in quantum optics, condensed matter physics, quantum information, and nonequilibrium statistical mechanics.

---

## Topics Covered

### Exact Models

Analytical and semi-analytical treatments of paradigmatic open quantum systems.

Included examples:

* Two-level atom under the Rotating Wave Approximation (RWA)
* Driven two-level atom
* Pure dephasing dynamics
* Comparison of OQuPy and QuTiP simulations

### Numerical Methods

Modern approaches for solving non-Markovian quantum dynamics.

Included methods:

* Coupled ordinary differential equation solvers
* Volterra integral equation solvers
* TEMPO (Time-Evolving Matrix Product Operator)
* HEOM (Hierarchical Equations of Motion)

---

## Repository Structure

```text
open-quantum-systems/
├── exact_models/
│   ├── two_level_atom_rwa.ipynb
│   ├── driven_two_level_atom_rwa.ipynb
│   ├── pure_dephasing.ipynb
│   └── oqupy_vs_qutip.ipynb
├── numerical_methods/
│   ├── coupled_ode_solver.ipynb
│   ├── volterra_integral_equation_solver.ipynb
│   ├── tempo_solver_demo.ipynb
│   ├── tempo_convergence_analysis.ipynb
│   └── heom_demo.ipynb
├── figures/
└── README.md
```

---

## Scientific Background

An open quantum system is a quantum subsystem interacting with external degrees of freedom (the environment or bath). Such interactions lead to:

* Decoherence
* Dissipation
* Relaxation
* Non-Markovian memory effects

The study of open quantum systems is fundamental to:

* Quantum optics
* Quantum thermodynamics
* Quantum information processing
* Condensed matter physics
* Quantum technologies

---

## Software Used

The notebooks may employ:

```bash
numpy
scipy
matplotlib
jupyter
qutip
oqupy
```

Additional dependencies may be required for specific demonstrations.

---

## Numerical Methods Included

### Coupled ODE Solvers

Direct numerical integration of dynamical equations.

### Volterra Integral Equations

Treatment of memory kernels and nonlocal temporal dynamics.

### TEMPO

Tensor-network-based approach for non-Markovian quantum dynamics.

### HEOM

Hierarchical Equations of Motion for strongly coupled system-environment interactions.

---

## Example Applications

* Spontaneous emission
* Driven quantum systems
* Pure dephasing
* Structured environments
* Non-Markovian dynamics
* Quantum transport
* Quantum thermodynamics

---

## References

### General Texts

1. H.-P. Breuer and F. Petruccione, *The Theory of Open Quantum Systems*.
2. U. Weiss, *Quantum Dissipative Systems*.
3. Á. Rivas and S. F. Huelga, *Open Quantum Systems*.

### Numerical Methods

4. Strathearn et al., *Efficient Non-Markovian Quantum Dynamics Using Time-Evolving Matrix Product Operators*.
5. Tanimura, *Numerically Exact Open Quantum Dynamics: HEOM Approach*.

---

## Intended Audience

This repository is suitable for:

* Graduate students learning open quantum systems
* Researchers exploring numerical techniques
* Quantum optics practitioners
* Computational physicists

---

## License

This repository is provided for educational and research purposes. Users are encouraged to cite the original literature and software packages associated with each method.

