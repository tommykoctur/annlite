# PQLite

`PQLite` is an **embedded** library for **Approximate Nearest Neighbor Search** (ANNS) using **Product Quantization** (PQ) algorithm. `

Bringing performance benefits in line with `Rust`, its memory safety, concurrency and accessibility to Machine Learning engineers make it a powerful additional choice for the deployment of performant, machine-learning powered applications.

## WARNING

`PQLite` is still in the very early stages of development. APIs can and will change (now is the time to make suggestions!). Important features are missing. Documentation is sparse.


## Design Goals

- **Capable**: Offer a complete 2D and 3D feature set
- **Simple**: Easy for newbies to pick up, but infinitely flexible for power users
- **Data Focused**: Data-oriented architecture using the Entity Component System paradigm
- **Modular**: Use only what you need. Replace what you don't like
- **Fast**: App logic should run quickly, and when possible, in parallel
- **Productive**: Changes should compile quickly ... waiting isn't fun

## About

- **Features**: A quick overview of PQlite's features.
- **Roadmap**: The PQLite team's development plan.
- **Introducing PQLite**: A blog post covering some of PQLite's features

## Install

- make sure you have the latest version of `rust` installed
- install `pqlite`

## Quick Start

## Benchmark

All experiments were performed with a Intel(R) Xeon(R) CPU @ 2.00GHz and Nvidia Tesla T4 GPU.

- [Yandex Research](https://research.yandex.com/datasets/biganns) Benchmarks for Billion-Scale Similarity Search



## References

- [hyperfine](https://github.com/sharkdp/hyperfine) Good UX example
- [PGM-index](https://github.com/gvinciguerra/PGM-index) State-of-the-art learned data structure that enables fast lookup, predecessor, range searches and updates in arrays of billions of items using orders of magnitude less space than traditional indexes
- [Xor Filters](https://lemire.me/blog/2019/12/19/xor-filters-faster-and-smaller-than-bloom-filters/) Faster and Smaller Than Bloom Filters


- [CVPR20 Tutorial](https://www.youtube.com/watch?v=SKrHs03i08Q&list=PLKQB14e0EJUWaTnwgQogJ3nSLzEFNn9d8&t=849s) Billion-scale Approximate Nearest Neighbor Search


## Research foundations of PQLite

- [ICML 2020](https://research.yandex.com/publications/280) Graph-based Nearest Neighbor Search: From Practice to Theory
- [CVPR 2019](https://research.yandex.com/publications/196) Unsupervised Neural Quantization for Compressed-Domain Similarity Search
- [ICML 2019](https://research.yandex.com/publications/188) Learning to Route in Similarity Graphs
- [NIPs 2018](https://research.yandex.com/publications/187) Non-metric Similarity Graphs for Maximum Inner Product Search
- [ACMMM 2018](https://arxiv.org/abs/1808.03969) Reconfigurable Inverted Index [code](https://github.com/matsui528/rii)
- [ECCV 2018](https://arxiv.org/abs/1802.02422) Revisiting the Inverted Indices for Billion-Scale Approximate Nearest Neighbors
- [CVPR 2016](https://research.yandex.com/publications/138) Efficient Indexing of Billion-Scale Datasets of Deep Descriptors
