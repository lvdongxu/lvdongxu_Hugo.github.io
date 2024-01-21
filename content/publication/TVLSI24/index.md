---
title: "FLNA: Flexibly Accelerating Feature Learning Networks for Large-Scale Point Clouds with Efficient Dataflow Decoupling"
authors:
- Dongxu Lyu
# author_notes:
# - "2nd Author"
# - "2nd Author"
date: "2024-01-14T00:00:00Z"
doi: "10.1109/TVLSI.2024.3355126"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-1-18T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Very Large Scale Integration (VLSI) Systems"
publication_short: In "IEEE Transactions on Very Large Scale Integration Systems (TVLSI)", 2024

abstract: Point cloud based 3D perception is poised to become a key workload on various applications. It always leverages a feature learning network (FLN) before backbones to obtain uniform representation from the scattered points. Grid-based FLN (GFLN) that partitions point clouds into uniform grids becomes the main category in recent state-of-the-art works. However, it heavily suffers from significant memory and com-putation inefficiency associated with high point sparsity and critical data dependency. To address these troubles, we pro-pose FLNA, a grid-based feature learning network accelerator with algorithm-architecture co-optimization for large-scale point clouds. At algorithm level, the dataflow-decoupling strategy is adopted to alleviate the processing bottlenecks from pipeline dependency, which also reduces 78.3% computation cost by exploiting the redundancy from inherent sparsity and special operators. Based on the algorithm co-optimization, an effective architecture is designed with efficient GFLN mapping and block-wise processing strategies. It manages to improve on-chip memory efficiency tremendously through diverse techniques, including linked-list-based block look-up-table and transposed feature organization. Extensively evaluated on representative benchmarks, FLNA achieves 69.9-264.4× speedup with more than 99% energy savings compared to multiple GPUs and CPU. It also demonstrates substantial performance boost over the state-of-the-art point cloud accelerators while providing superior support of large-scale point clouds.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- IEEE Transaction
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
