# QuantumKitHub

**A Julia ecosystem for tensor networks and quantum many-body physics.**

## About

QuantumKitHub develops and maintains a suite of interoperable Julia packages for
large-scale tensor network computations. The ecosystem spans from low-level tensor
contractions and symmetry-aware data structures to high-level algorithms for simulating
quantum many-body systems.

## Ecosystem

### Tensor Network Algorithms

| Package | Description | |
|---------|-------------|:-:|
| [MPSKit.jl](https://github.com/QuantumKitHub/MPSKit.jl) | Simulating quantum many-body systems using Matrix Product States | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MPSKit.jl/) |
| [PEPSKit.jl](https://github.com/QuantumKitHub/PEPSKit.jl) | Algorithms for Projected Entangled Pair States | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/PEPSKit.jl/) |
| [MPSKitModels.jl](https://github.com/QuantumKitHub/MPSKitModels.jl) | Pre-built models for MPSKit.jl | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MPSKitModels.jl/) |

### Tensor Foundations

| Package | Description | |
|---------|-------------|:-:|
| [TensorKit.jl](https://github.com/QuantumKitHub/TensorKit.jl) | Large-scale tensor computations, with a hint of category theory | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorKit.jl/) |
| [StridedViews.jl](https://github.com/QuantumKitHub/StridedViews.jl) | Representing strided views into dense arrays | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/StridedViews.jl/) |
| [Strided.jl](https://github.com/QuantumKitHub/Strided.jl) | Efficient operations on strided arrays | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/Strided.jl/) |
| [TensorOperations.jl](https://github.com/QuantumKitHub/TensorOperations.jl) | Tensor contractions and related operations | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorOperations.jl/) |
| [MatrixAlgebraKit.jl](https://github.com/QuantumKitHub/MatrixAlgebraKit.jl) | Extensible matrix algebra primitives | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MatrixAlgebraKit.jl/) |
| [SparseArrayKit.jl](https://github.com/QuantumKitHub/SparseArrayKit.jl) | Sparse multidimensional arrays (DOK format) with TensorOperations.jl support | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/SparseArrayKit.jl/) |

### Symmetries & Categories

| Package | Description | |
|---------|-------------|:-:|
| [TensorKitSectors.jl](https://github.com/QuantumKitHub/TensorKitSectors.jl) | Objects in fusion categories | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorKitSectors.jl/) |
| [SUNRepresentations.jl](https://github.com/QuantumKitHub/SUNRepresentations.jl) | SU(N) Clebsch-Gordan coefficients | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/SUNRepresentations.jl/) |
| [CategoryData.jl](https://github.com/QuantumKitHub/CategoryData.jl) | Reading in categorical data for TensorKit | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/CategoryData.jl/) |
| [QWignerSymbols.jl](https://github.com/QuantumKitHub/QWignerSymbols.jl) | q-deformed Wigner symbols and related quantities | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/QWignerSymbols.jl/) |

### Extensions & Utilities

| Package | Description | |
|---------|-------------|:-:|
| [TensorKitManifolds.jl](https://github.com/QuantumKitHub/TensorKitManifolds.jl) | Tools for isometric and unitary tensor manifolds | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorKitManifolds.jl/) |
| [TensorKitTensors.jl](https://github.com/QuantumKitHub/TensorKitTensors.jl) | A collection of specific TensorMaps for TensorKit.jl | |
| [MultiTensorKit.jl](https://github.com/QuantumKitHub/MultiTensorKit.jl) | Multi-tensor extensions for TensorKit.jl | |
| [TBLIS.jl](https://github.com/QuantumKitHub/TBLIS.jl) | Julia wrapper for the TBLIS tensor contraction library | |
| [TensorOperationsTBLIS.jl](https://github.com/QuantumKitHub/TensorOperationsTBLIS.jl) | TBLIS backend for TensorOperations.jl | |

## Documentation

Aggregated documentation for the ecosystem is available at
[quantumkithub.github.io/QuantumKitHubDocs.jl](https://quantumkithub.github.io/QuantumKitHubDocs.jl/).
Individual package docs are linked in the tables above.

## Contributing

Contributions are welcome across all packages. Please open issues or pull requests on the
relevant repository. For questions and discussions, use the
[Julia Discourse](https://discourse.julialang.org/) with the `tensor-network` tag.
