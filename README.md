# CDSH-UHCL
A Unified Hierarchical Contrastive Loss for robust representation learning.

This repository contains the `CDSH-UHCL.ipynb` notebook implementing the contrastive representation learning pipeline for inlier/outlier/noise separation using a hierarchical formulation.

## Notebook
- `CDSH-UHCL.ipynb`

## Overview
The project explores a hierarchical contrastive objective that models:
- inlier structure,
- outlier separation,
- noise rejection,
- and fine/coarse semantic consistency.

The implementation is built in PyTorch and is designed for CIFAR-100 inlier experiments with CIFAR-10 and SVHN as OOD sources.

## Quick start
1. Open `CDSH-UHCL.ipynb` in Jupyter or Colab.
2. Run the notebook cells in sequence.
3. The notebook includes dataset construction, model definition, UHCL training, evaluation, and plotting utilities.

## Notes
This project is intended as a research-oriented implementation and may require a GPU-enabled environment for full training runs.
