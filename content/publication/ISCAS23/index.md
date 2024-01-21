---
title: 'O^3NMS: An Out-Of-Order-Based Low-Latency Accelerator for Non-Maximum Suppression'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Yuzhou Chen
- Jinming Zhang 
- Dongxu Lyu
- Xi Yu
- Guanghui He

# Author notes (optional)
author_notes:
  - '3rd Author'
#   - 'Equal contribution'

date: '2023-07-21T00:00:00Z'
doi: ' 10.1109/ISCAS46773.2023.10181731'


# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*
publication_short: In *2023 IEEE International Symposium on Circuits and Systems (ISCAS)*, 2023
# publication_short: In *ISCAS'23*
abstract: Non-maximum suppression (NMS) is an important post-processing method to eliminate overlapping bounding boxes in object detection neural networks. Suffering from quadratic computational complexity and frequent memory access, NMS has become a bottleneck of detection latency. To deal with this problem, we propose out-of-order NMS (O 3 NMS), a hardware- software co-optimization approach to reduce latency as well as area overhead of NMS accelerator. In order to reduce startup latency, we devise the O3NMS algorithm that removes pre-sort operation. To efficiently support O 3 NMS algorithm, we design a specialized hardware accelerator. Our design has been implemented in both Xilinx FPGA and SIMC 40nm technology. Experiments demonstrate O 3 NMS accelerator achieves 2.51 x speedup as well as 37 % reduction in FPGA source utilization compared with the state-of-the-art (SOTA) NMS accelerator.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/10181731'
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
