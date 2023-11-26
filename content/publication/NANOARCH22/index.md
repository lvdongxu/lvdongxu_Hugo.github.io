---
title: 'An Efficient Stochastic Convolution Accelerator based on Pseudo-Sobol Sequences'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Aokun Hu
  - Wenjie Li
  - *Dongxu Lyu*

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2023-05-31T00:00:00Z'
doi: '10.1145/3565478.3572543'


# Schedule page publish date (NOT publication's date).
publishDate: '2023-11-26T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *17th ACM International Symposium on Nanoscale Architectures (NANOARCH)*
publication_short: In *NANOARCH'22*

abstract: Stochastic computing (SC) has been recognized as an efficient technique to reduce the hardware consumption of a convolution neural network (CNN) accelerator. An SC-CNN needs a long SC sequence length to produce accurate results, which leads to a low throughput. In order to achieve better accuracy and higher throughput, highly parallelized SC-CNNs based on Sobol sequences have been extensively used. However, high parallelism leads to undesirable hardware overhead. To solve this problem, this paper proposes Pseudo-Sobol sequences and accordingly develops an efficient parallel computation-conversion hybrid convolution architecture, which fuses the SC-computation units and S2B units. With negligible accuracy loss, the proposed architecture can increase energy and area efficiency by 41% and 36%, respectively.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3565478.3572543'
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
