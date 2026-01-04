# sparse_neural_networks

This repository contains code from a collaborative project exploring efficiency–performance trade-offs in over-parameterized neural networks.

The primary focus is on low-rank factorization of fully connected layers in a VGG16 model trained on the Linnaeus 5 image dataset, which significantly reduces training time with only a modest drop in accuracy.

An additional notebook explores input-level sparsification using Laplacian pyramids as a supplementary direction.

Due to course environment and dataset setup, the full pipeline may require minor reconfiguration to reproduce the exact results. The core modeling choices and evaluation logic are documented here.
