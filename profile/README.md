# FAlCon — Autotuning for Quantum-Dot Qubits ⚛️🚀

FAlCon is an open-source ecosystem for automation, measurement, and autotuning of quantum-dot spin qubit devices.

Modern quantum-dot experiments rely on increasingly complex instrumentation and tuning procedures. FAlCon aims to make these workflows more reproducible, portable, and scalable by providing a common foundation for instrument control, data acquisition, a domain-specific language (DSL) for workflow development, autotuning algorithms, simulation, and experimental automation.

![FAlCon](https://img.shields.io/badge/FAlCon-v2.0.0-success)
![Standard_Library](https://img.shields.io/badge/Std--Lib-v1.2.4-success)
![Instrument_Controller](https://img.shields.io/badge/Instrument_Controller-v1.0.0-success)
![license-multi](https://img.shields.io/badge/license-MPL%20%2F%20BSD-blue)

---

## Releases

### FAlCon Framework

The core autotuning framework for building, testing, and deploying automated tuning workflows.

**Release:** [v2.0.0](https://github.com/falcon-autotuning/falcon/releases/tag/v2.0.0)

### FAlCon Standard Library

The standard library for the FAlCon DSL, providing language primitives, measurement abstractions, data structures, and reusable building blocks used to implement experimental and autotuning workflows.

**Release:** [v1.2.4](https://github.com/falcon-autotuning/std-lib/releases/tag/v1.2.4)

### Instrument Controller

Hardware abstraction, measurement orchestration, data acquisition, and laboratory instrument integration infrastructure for FAlCon-based workflows.

**Release:** [v1.0.0](https://github.com/falcon-autotuning/instrument-controller/releases/tag/v1.0.0)

---

## What FAlCon Provides

### FAlCon DSL

A domain-specific language for expressing measurement routines, tuning procedures, experimental workflows, and autotuning algorithms in a portable and reproducible manner.

### Instrument Control

Unified interfaces for laboratory instruments and experimental hardware.

### Measurement & Data Infrastructure

Tools for measurement acquisition, cataloging, storage, orchestration, and analysis.

### Autotuning Algorithms

Reusable tuning primitives, optimization routines, characterization procedures, and automated decision-making workflows.

### Simulation & Testing

Development and validation environments that allow workflows to be tested before deployment on physical hardware.

---

## Getting Started

- Install the latest FAlCon release.
- Install the Instrument Controller.
- Explore the repositories within this organization for instrument integrations, autotuning workflows, simulation environments, visualization tools, and supporting infrastructure.

Repositories within the FAlCon DSL ecosystem are designed to be composable. Individual components may be used independently or combined into larger automated measurement and tuning workflows.

---

## Contributing

Contributions of all sizes are welcome.

You can help by:

- Improving documentation
- Reporting bugs and issues
- Contributing autotuning algorithms
- Adding instrument integrations
- Expanding simulation and testing infrastructure
- Building visualization and operator tooling
- Developing libraries and tooling for the FAlCon DSL

Please review our [Code of Conduct](https://github.com/falcon-autotuning/.github/blob/main/CODE_OF_CONDUCT.md) before contributing.

---

## Governance

FAlCon is developed in the open by maintainers and contributors across the community.

- Pull requests are reviewed prior to merging.
- Automated testing is encouraged where applicable.
- Major design discussions take place through issues and pull requests.

---

## Licensing

Repositories within the FAlCon ecosystem are released under either MPL-2.0 or BSD-3-Clause licenses depending on the component.

Refer to the LICENSE file of each repository for specific terms.

---

## Citation

If FAlCon contributes to your research, please cite:

> Tyler J. Kovach et al., *FAlCon: An Open-Source Framework for Autotuning Quantum Dot Devices*  
> https://arxiv.org/pdf/2603.16650
