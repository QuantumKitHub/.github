<div align="center">

# QuantumKitHub

**A Julia ecosystem for tensor networks and quantum many-body physics.**

[![Docs hub](https://img.shields.io/badge/docs-ecosystem-4063D8)](https://quantumkithub.github.io/QuantumKitHubDocs.jl/dev/)
[![Julia](https://img.shields.io/badge/julia-1.10+-389826)](https://julialang.org)

</div>

<table>
<tr>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/TensorKit.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/TensorKit.jl/main/docs/src/assets/logo_readme.svg" height="80" alt="TensorKit.jl"></a><br><b><a href="https://github.com/QuantumKitHub/TensorKit.jl">TensorKit.jl</a></b><br><sub>Tensors with symmetries, a hint of category theory</sub><br><a href="https://quantumkithub.github.io/TensorKit.jl/stable/">docs</a></td>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/TensorOperations.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/TensorOperations.jl/main/docs/src/assets/logo_readme.svg" height="80" alt="TensorOperations.jl"></a><br><b><a href="https://github.com/QuantumKitHub/TensorOperations.jl">TensorOperations.jl</a></b><br><sub>Tensor contractions with the @tensor macro</sub><br><a href="https://quantumkithub.github.io/TensorOperations.jl/stable/">docs</a></td>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/MatrixAlgebraKit.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/MatrixAlgebraKit.jl/main/docs/src/assets/logo.svg" height="80" alt="MatrixAlgebraKit.jl"></a><br><b><a href="https://github.com/QuantumKitHub/MatrixAlgebraKit.jl">MatrixAlgebraKit.jl</a></b><br><sub>Extensible matrix factorizations</sub><br><a href="https://quantumkithub.github.io/MatrixAlgebraKit.jl/stable/">docs</a></td>
</tr>
<tr>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/MPSKit.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/MPSKit.jl/main/docs/src/assets/logo_readme.svg" height="80" alt="MPSKit.jl"></a><br><b><a href="https://github.com/QuantumKitHub/MPSKit.jl">MPSKit.jl</a></b><br><sub>Matrix product state algorithms</sub><br><a href="https://quantumkithub.github.io/MPSKit.jl/stable/">docs</a></td>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/PEPSKit.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/PEPSKit.jl/main/docs/src/assets/logo_readme.svg" height="80" alt="PEPSKit.jl"></a><br><b><a href="https://github.com/QuantumKitHub/PEPSKit.jl">PEPSKit.jl</a></b><br><sub>Projected entangled pair state algorithms</sub><br><a href="https://quantumkithub.github.io/PEPSKit.jl/stable/">docs</a></td>
<td align="center" width="33%"><a href="https://github.com/QuantumKitHub/TNRKit.jl"><img src="https://raw.githubusercontent.com/QuantumKitHub/TNRKit.jl/master/docs/src/assets/logo_readme.svg" height="80" alt="TNRKit.jl"></a><br><b><a href="https://github.com/QuantumKitHub/TNRKit.jl">TNRKit.jl</a></b><br><sub>Tensor network renormalization</sub><br><a href="https://quantumkithub.github.io/TNRKit.jl/stable/">docs</a></td>
</tr>
</table>

<details>
<summary><b>All packages</b></summary>

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
| [WignerSymbols.jl](https://github.com/QuantumKitHub/WignerSymbols.jl) | Wigner symbols and related quantities | |
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
</details>

Contributions are welcome across all packages: please open an issue or pull request on the relevant repository.
