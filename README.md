# pw2qmcpack
pw2qmcpack converts the DFT orbitals calculated by [Quantum ESPRESSO](https://www.quantum-espresso.org/) into a [QMCPACK](https://qmcpack.org/) readable format.

Users should not build the source code of this repository directly but build QE via CMake with the option `-DQE_ENABLE_PLUGINS=pw2qmcpack` added.
We don't support enabling pw2qmcpack in QE configure script.

[![ci-qe](https://github.com/QMCPACK/pw2qmcpack/actions/workflows/ci-github-actions.yaml/badge.svg)](https://github.com/QMCPACK/pw2qmcpack/actions/workflows/ci-github-actions.yaml)
