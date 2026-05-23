# Seeing Superposition

Replication of the $W^T W$ heatmap experiment from [Elhage et al., 2022](https://transformer-circuits.pub/2022/toy_model/index.html).

Writeup: [Seeing Superposition](https://yeginbay.com/seeing-superposition)

## What's here

A small ReLU autoencoder ($n=20$ features, $m=5$ hidden dimensions) trained across a sparsity sweep. The notebook reproduces the heatmap of $W^T W$ for $S \in \{0, 0.7, 0.9, 0.97, 0.99\}$, showing how feature representations shift from orthogonal to superposed as sparsity rises.
