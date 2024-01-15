---
title: 2024/01 One paper is accepted by IEEE TVLSI!
subtitle: The extended paper of our **FLNA** (DAC'23) is accepted by IEEE TVLSI this January!

# Summary for listings and search engines
summary: The extended paper of our **FLNA** (DAC'23) is accepted by IEEE TVLSI this January!.

# Link this post with a project
projects: []

# Date published
date: '2024-1-15T00:00:00Z'

# Date updated
lastmod: '2024-1-15T00:00:00Z'

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/CpkOjOcXdUY)'
  focal_point: ''
  placement: 2
  preview_only: false

authors:
  - 吕东旭
  - Dongxu Lyu

tags:
  - Transaction

# categories:
#   - Demo
#   - 教程
---

## Abstract

Point cloud based 3D perception is poised to become a key workload on various applications. It always leverages a feature learning network (FLN) before backbones to obtain uniform representation from the scattered points. Grid-based FLN (GFLN) that partitions point clouds into uniform grids becomes the main category in recent state-of-the-art works. However, it heavily suffers from significant memory and computation inefficiency associated with high point sparsity and critical data dependency. To address these troubles, we propose FLNA, a grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. At algorithm level, the dataflow-decoupling strategy is adopted to alleviate the processing bottlenecks from pipeline dependency, which also reduces 78.3% computation cost by exploiting the redundancy from inherent sparsity and special operators. Based on the algorithm co-optimization, an effective architecture is designed with efficient GFLN mapping and block-wise processing strategies. It manages to improve on-chip memory efficiency tremendously through diverse techniques, including linked-list-based block look-up-table and transposed feature organization. Extensively evaluated on representative benchmarks, FLNA achieves 69.9-264.4× speedup with more than 99% energy savings compared to multiple GPUs and CPU. It also demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds.