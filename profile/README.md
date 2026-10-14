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
| [MPSKit.jl](https://github.com/QuantumKitHub/MPSKit.jl) | Simulating quantum many-body systems using Matrix Product States | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MPSKit.jl/stable/) |
| [PEPSKit.jl](https://github.com/QuantumKitHub/PEPSKit.jl) | Algorithms for Projected Entangled Pair States | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/PEPSKit.jl/stable/) |
| [TNRKit.jl](https://github.com/QuantumKitHub/TNRKit.jl) | Algorithms for Tensor Network Renormalisation | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TNRKit.jl/stable/) |
| [MPSKitModels.jl](https://github.com/QuantumKitHub/MPSKitModels.jl) | Pre-built models for MPSKit.jl | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MPSKitModels.jl/stable/) |

### Tensor Foundations

| Package | Description | |
|---------|-------------|:-:|
| [TensorKit.jl](https://github.com/QuantumKitHub/TensorKit.jl) | Large-scale tensor computations, with a hint of category theory | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorKit.jl/stable/) |
| [VectorInterface.jl](https://github.com/QuantumKitHub/VectorInterface.jl) | A Julia interface for working with vector-like objects | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/VectorInterface.jl/stable/) |
| [StridedViews.jl](https://github.com/QuantumKitHub/StridedViews.jl) & [Strided.jl](https://github.com/QuantumKitHub/Strided.jl) | Representing strided views into dense arrays and efficient operations on them | |
| [TensorOperations.jl](https://github.com/QuantumKitHub/TensorOperations.jl) | Tensor contractions and related operations | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorOperations.jl/stable/) |
| [MatrixAlgebraKit.jl](https://github.com/QuantumKitHub/MatrixAlgebraKit.jl) | Extensible matrix algebra primitives | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MatrixAlgebraKit.jl/stable/) |
| [SparseArrayKit.jl](https://github.com/QuantumKitHub/SparseArrayKit.jl) | Sparse multidimensional arrays (DOK format) with TensorOperations.jl support | |
| [BlockTensorKit.jl](https://github.com/QuantumKitHub/BlockTensorKit.jl) | TensorKit extension for working with block(sparse) TensorMaps | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/BlockTensorKit.jl/stable/) |

### Symmetries & Categories

| Package | Description | |
|---------|-------------|:-:|
| [TensorKitSectors.jl](https://github.com/QuantumKitHub/TensorKitSectors.jl) | Objects in fusion categories | [![docs](https://img.shields.io/badge/docs-dev-blue)](https://quantumkithub.github.io/TensorKitSectors.jl/dev/) |
| [SUNRepresentations.jl](https://github.com/QuantumKitHub/SUNRepresentations.jl) | SU(N) Clebsch-Gordan coefficients | |
| [CategoryData.jl](https://github.com/QuantumKitHub/CategoryData.jl) | Reading in categorical data for TensorKit | |
| [QWignerSymbols.jl](https://github.com/QuantumKitHub/QWignerSymbols.jl) | q-deformed Wigner symbols and related quantities | |

### Extensions & Utilities

| Package | Description | |
|---------|-------------|:-:|
| [TensorKitManifolds.jl](https://github.com/QuantumKitHub/TensorKitManifolds.jl) | Tools for isometric and unitary tensor manifolds | |
| [TensorKitTensors.jl](https://github.com/QuantumKitHub/TensorKitTensors.jl) | A collection of specific TensorMaps for TensorKit.jl | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/TensorKitTensors.jl/stable/) |
| [MultiTensorKit.jl](https://github.com/QuantumKitHub/MultiTensorKit.jl) | Multi-tensor extensions for TensorKit.jl | |
| [TBLIS.jl](https://github.com/QuantumKitHub/TBLIS.jl) | Julia wrapper for the TBLIS tensor contraction library | |
| [TensorOperationsTBLIS.jl](https://github.com/QuantumKitHub/TensorOperationsTBLIS.jl) | TBLIS backend for TensorOperations.jl | |
| [TensorOperationsHPTT.jl](https://github.com/QuantumKitHub/TensorOperationsHPTT.jl) | HPTT (High-Performance Tensor Transpose) backend for TensorOperations.jl | |
| [QuasiStrided.jl](https://github.com/QuantumKitHub/QuasiStrided.jl) | Native-Julia dense tensor contraction engine, available as a TensorOperations.jl backend | |

### General-Purpose Tools

| Package | Description | |
|---------|-------------|:-:|
| [MemoizationKit.jl](https://github.com/QuantumKitHub/MemoizationKit.jl) | Memoization with bounded memory, persistent disk caching, and a live terminal dashboard | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/MemoizationKit.jl/stable/) |
| [AlgorithmsInterface.jl](https://github.com/QuantumKitHub/AlgorithmsInterface.jl) | A small, composable interface for iterative algorithms | [![docs](https://img.shields.io/badge/docs-stable-blue)](https://quantumkithub.github.io/AlgorithmsInterface.jl/stable/) |

## Documentation

Aggregated documentation for the ecosystem is available at
[quantumkithub.github.io/QuantumKitHubDocs.jl](https://quantumkithub.github.io/QuantumKitHubDocs.jl/dev/).
Individual package docs are linked in the tables above.

## Contributing

Contributions are welcome across all packages. Please open issues or pull requests on the
relevant repository. For questions and discussions, use the
[Julia Discourse](https://discourse.julialang.org/) with the `tensor-network` tag.
