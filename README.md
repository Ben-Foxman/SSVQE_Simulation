# SSVQE Simulation - A workflow for running VQE/SSVQE optimization algorithms.

VQE, or the Variational Quantum Eigensolver, is a one-loop optimization procedure for calulcating ground state energy levels of Hamiltonians.

The SSVQE, or subspace search optimization algortihm, is an extension to VQE to calculate the first k energy eigenstates of a Hamiltionian in O(k)
time. To learn about how SSVQE works, see the paper here: https://arxiv.org/abs/1810.09434

## How to Use This Notebook
- This notebook is a user-friendly way to run the SSVQE algorithm with specified parameters, which can can be specified in the 
modifiable parameters area in section 1. 
- Information about running experiments are written to SSVQE.log, inclduind any warnings/errors. 
- Results of completed experiments are stored in VQE_results.df, which tracks all completed experiments. Please do not modify this file. 