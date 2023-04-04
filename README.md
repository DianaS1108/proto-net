# proto-net

This repository contains our implementation of the Prototypical Network for both few-shot and zero-shot learning [(Snell et al., 2017)](https://arxiv.org/abs/1703.05175),
as part of the project for the MLMI 4 Advanced Machine Learning module at the University of Cambridge.

Specifically,
- `few_shot_omniglot.ipynb` is for few-shot learning on the Omniglot dataset
- `zero_shot.ipynb` is for zero-shot learning on the Caltech-UCSD Birds (CUB) 200-2011 dataset

To replicate results in the original paper, we have also performed few-shot learning on the mini-ImageNet dataset.
The code is largely similar to that for Omniglot (except from the dataset) and is omitted here.

All data used is downloadable online:
- Omniglot dataset (and split): from [the original implementation](https://github.com/jakesnell/prototypical-networks)
- CUB dataset: from https://www.vision.caltech.edu/datasets/cub_200_2011/
- CUB - extracted image feature by GoogleNet: from https://github.com/reedscot/cvpr2016

Also, the mini-ImageNet dataset in the used split is downloaded from https://lyy.mpi-inf.mpg.de/mtl/download/Lmzjm9tX.html.
