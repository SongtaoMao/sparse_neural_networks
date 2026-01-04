# Efficiency–Performance Trade-offs in Sparse Neural Networks

This repository contains code from a collaborative project studying efficiency–performance trade-offs in over-parameterized neural networks through multiple sparsification strategies.

We investigate two complementary and equally important approaches.  
The first replaces large fully connected layers in a VGG16 model with low-rank factorized layers, significantly reducing training time while preserving most of the predictive performance.  
The second explores input-level sparsification using Laplacian pyramid decompositions, analyzing how multi-scale representations impact accuracy and computational efficiency.

Both approaches are evaluated on the Linnaeus 5 image classification dataset, with experiments highlighting different trade-offs between model efficiency, stability, and accuracy.  
Together, these results demonstrate how exploiting structural redundancy at different stages of the pipeline can lead to faster and more scalable neural network systems.

Note: Reproducing the exact results may require minor reconfiguration. The core modeling ideas and evaluation logic are fully documented in the notebooks.
