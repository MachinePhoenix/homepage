---
title: "Towards Noise-Robust Medical Segmentation via Chebyshev-Attention-Based UNet"
authors:
- admin
- Ziyang Zheng
- Wenrui Dai
- Chenglin Li
- Junni Zou
- Hongkai Xiong

author_notes:
- ""
date: "2025-06-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]


# Publication name and optional abbreviated publication name.
publication: "WACV 2026"
publication_short: ""

abstract: "Existing medical image segmentation methods based on UNet architectures exhibit significant noise sensitivity due to cascaded feature propagation in symmetric encoder-decoder paths and linear feature fusion mechanisms. To address this, we propose \textbf{CASUNet (Chebyshev-Attention-Based Semi-UNet)}, a noise-resilient framework integrating a \textbf{Semi-UNet} backbone with a novel \textbf{CPA (Chebyshev Polynomial Aggregation)} module. Specifically, CASUNet aggregates hierarchical representations by grouping multi-scale features into distinct low- and high-resolution branches rather than sequentially upsampling, effectively mitigating noise sensitivity through isolated feature processing. Furthermore, CASUNet introduces the CPA mechanism where hierarchical features are expanded into orthogonal polynomial terms, enhancing feature fusion capacity beyond linear aggregation while ensuring noise robustness through a carefully designed polynomial-normalization. The proposed model delivers superior noise immunity and competitive performance compared to state-of-the-art approaches with significantly enhanced parameter efficiency."

# Summary. An optional shortened abstract.
summary: Medical Image Segmentation, Noise, UNet, Chebyshev Polynomial.

# tags:
# - Source Themes
featured: false


links:
# - name: Custom Link
#   url: http://example.org
url_pdf: CASUNet.pdf
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/). -->
