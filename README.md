# General Purpose Ray Tracing Cores

A curated list of papers that repurpose GPU **ray tracing (RT) cores** — hardware originally designed for graphics — to accelerate **non-rendering** workloads. RT cores provide fast BVH traversal and ray–primitive intersection, which map surprisingly well onto spatial queries, clustering, graph algorithms, and other compute problems.

Contributions welcome — open a PR to add missing papers.

---

## Contents

- [Nearest Neighbor & Similarity Search](#nearest-neighbor--similarity-search)
- [Spatial Indexing & Queries](#spatial-indexing--queries)
- [Database Systems](#database-systems)
- [Clustering](#clustering)
- [Graph Algorithms](#graph-algorithms)
- [Scientific & Numerical Computing](#scientific--numerical-computing)
- [Systems & Architecture](#systems--architecture)

---

## Nearest Neighbor & Similarity Search

| Year | Venue | Paper |
|------|-------|-------|
| 2022 | PPoPP | [RTNN: Accelerating Neighbor Search Using Hardware Ray Tracing](https://doi.org/10.1145/3503221.3508409) |
| 2023 | ICS | [RT-kNNS Unbound: Using RT Cores to Accelerate Unrestricted Neighbor Search](https://doi.org/10.1145/3577193.3593738) |
| 2024 | ASPLOS | [Juno: Optimizing High-Dimensional Approximate Nearest Neighbour Search with Sparsity-Aware Algorithm and Ray-Tracing Core Mapping](https://doi.org/10.1145/3620665.3640360) |
| 2024 | ICS | [Arkade: k-Nearest Neighbor Search With Non-Euclidean Distances using GPU Ray Tracing](https://doi.org/10.1145/3650200.3656601) |

## Spatial Indexing & Queries

| Year | Venue | Paper |
|------|-------|-------|
| 2024 | FGCS | [Accelerating Range Minimum Queries with Ray Tracing Cores](https://doi.org/10.1016/j.future.2024.03.040) |
| 2024 | ICS | [RayJoin: Fast and Precise Spatial Join](https://doi.org/10.1145/3650200.3656610) |
| 2024 | MICRO | [Extending GPU Ray-Tracing Units for Hierarchical Search Acceleration](https://doi.org/10.1109/MICRO61859.2024.00079) |
| 2025 | PPoPP | [LibRTS: A Spatial Indexing Library by Ray Tracing](https://doi.org/10.1145/3710848.3710850) |
| 2026 | ICS | [X-HD: Fast Hausdorff Distance Computation with Ray Tracing](https://rubaolee.github.io/paper_pdfs/2026-xhd.pdf) |

## Database Systems

| Year | Venue | Paper |
|------|-------|-------|
| 2023 | VLDB | [RTIndeX: Exploiting Hardware-Accelerated GPU Raytracing for Database Indexing](https://arxiv.org/abs/2303.01139) |
| 2024 | VLDB | [RTScan: Efficient Scan with Ray Tracing Cores](https://doi.org/10.14778/3648160.3648183) |
| 2025 | VLDB | [RayDB: Building Databases with Ray Tracing Cores](https://doi.org/10.14778/3772181.3772185) |

## Clustering

| Year | Venue | Paper |
|------|-------|-------|
| 2023 | IPDPS | [RT-DBSCAN: Accelerating DBSCAN using Ray Tracing Hardware](https://doi.org/10.1109/IPDPS54959.2023.00100) |

## Graph Algorithms

| Year | Venue | Paper |
|------|-------|-------|
| 2025 | SIGMETRICS | [A Case Study for Ray Tracing Cores: Performance Insights with Breadth-First Search and Triangle Counting in Graphs](https://doi.org/10.1145/3727108) |

## Scientific & Numerical Computing

| Year | Venue | Paper |
|------|-------|-------|
| 2025 | PPoPP | [RT-BarnesHut: Accelerating Barnes–Hut Using Ray-Tracing Hardware](https://doi.org/10.1145/3710848.3710885) |
| 2025 | ISCA | [RTSpMSpM: Harnessing Ray Tracing for Efficient Sparse Matrix Computations](https://doi.org/10.1145/3695053.3731072) |
| 2026 | ICS | [Rethinking Collision Detection on GPU Ray Tracing Architecture](https://arxiv.org/abs/2604.23520) |

## Systems & Architecture

| Year | Venue | Paper |
|------|-------|-------|
| 2025 | ISCA | [Heliostat: Harnessing Ray Tracing Accelerators for Page Table Walks](https://doi.org/10.1145/3695053.3731011) |
