# GFFMERGE: Efficient Merging of Graph Neural Force Fields

![Objective](objective.png)

## Overview
Graph Neural Networks (GNNs) have significantly advanced Neural Force Fields (NFFs) for molecular dynamics simulations, enabling high-fidelity predictions at a fraction of the cost of quantum mechanical calculations. Generalizing these potentials across diverse chemical spaces remains challenging, and efficient methods for merging GNN-based force fields are still limited. GFFMERGE introduces a principled, closed-form merging framework that exploits the linear structure of message-passing layers and formulates merging as a convex embedding-alignment problem with an analytical solution. We provide systematic benchmarking across molecular (MD17, MD22), bulk material (LiPS20), and large-scale graph learning benchmarks, showing consistent improvements over prior merging methods with up to 3 orders of magnitude speedup.

## Repository structure
- `ORB/` — ORB experiments, scripts, and notebooks.
- `M3GNet/` — M3GNet experiments, scripts, and notebooks

## Setup
- `ORB/` — Please find in ORB/README.md
- `M3GNet/` — Please find in M3GNET/README.md
## References

If you use this code, please cite our papers:

```bibtex
@inproceedings{
garg2025gnnmerge,
title={{GNNMERGE}: {MERGING} {OF} {GNN} {MODELS} {WITHOUT} {ACCESSING} {TRAINING} {DATA}},
author={Vipul Garg and Ishita Thakre and Sayan Ranu},
booktitle={Workshop on Neural Network Weights as a New Data Modality},
year={2025},
url={https://openreview.net/forum?id=DIYMPC16Pi}
}
```

## Earlier work

This work builds on our previous work done on generic GNNs (GIN, GAT, NodeFormer, GraphSAGE). If interested, please check out the following repo for the source code - [GNNMerge](https://github.com/idea-iitd/GNNMerge)

## License

The GFFMerge code is published and distributed under the [Apache 2.0 License](LICENCE).
