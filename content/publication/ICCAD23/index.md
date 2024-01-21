---
title: 'SpOctA: A 3D Sparse Convolution Accelerator with Octree-Encoding-Based Map Search and Inherent Sparsity-Aware Processing'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Dongxu Lyu
- Zhenyu Li
- Yuzhou Chen
- Jinming Zhang
- Ningyi Xu
- Guanghui He

# Author notes (optional)
# author_notes:
#   - '1st author'

date: '2023-11-30T00:00:00Z'
doi: '10.1109/ICCAD57390.2023.10323728'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-04T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.

publication: In *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*
publication_short: In *2023 IEEE/ACM International Conference on Computer Aided Design (ICCAD)*, 2023
# publication_short: In *ICCAD'23*

abstract: Point-cloud-based 3D perception has attracted great attention in various applications including robotics, autonomous driving and AR/VR. In particular, the 3D sparse convolution (SpConv) network has emerged as one of the most popular backbones due to its excellent performance. However, it poses severe challenges to real-time perception on general-purpose platforms, such as lengthy map search latency, high computation cost, and enormous memory footprint. In this paper, we propose SpOctA, a SpConv accelerator that enables high-speed and energy-efficient point cloud processing. SpOctA parallelizes the map search by utilizing algorithm-architecture co-optimization based on octree encoding, thereby achieving 8.8-21.2x search speedup. It also attenuates the heavy computational workload by exploiting inherent sparsity of each voxel, which eliminates computation redundancy and saves 44.4-79.1% processing latency. To optimize on-chip memory management, a SpConv-oriented non-uniform caching strategy is introduced to reduce external memory access energy by 57.6% on average. Implemented on a 40nm technology and extensively evaluated on representative benchmarks, SpOctA rivals the state-of-the-art SpConv accelerators by 1.1-6.9x speedup with 1.5-3.1x energy efficiency improvement.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10323728'
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
