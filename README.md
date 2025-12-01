# The Nuclear Confectionery

The Nuclear Confectionery is a modular framework for simulating the full dynamical evolution of relativistic heavy-ion collisions. Its core hydrodynamic module, CCAKE 2.0, represents a major advance over previous SPH-based relativistic hydrodynamic codes.

CCAKE 2.0 simultaneously evolves energy–momentum and multiple conserved charges (B, S, Q) with a four-dimensional equation of state, and can be run in either Cartesian or hyperbolic coordinates, enabling consistent simulations from the RHIC Beam Energy Scan to LHC energies.
---

## Physics Features

- Full evolution of energy-momentum and conserved charges (B, S, Q)
- 4D equation of state (T, μB, μS, μQ)
- Optional Cartesian or hyperbolic coordinates
- Source-term contribution for jet–medium coupling and dynamical initialization 
- Supports multiple equations of motion:
  - Israel–Stewart
  - DNMR


---

## HPC and Software Features

- GPU-ready performance via Kokkos / Cabana
- YAML-based configuration
- Designed for event-by-event simulations

---

