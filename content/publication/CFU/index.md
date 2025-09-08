---
title: "Parameter-Efficient Cross-Layer Feature Fusion via Chebyshev Polynomial Unit"
authors:
- admin
- Jiarui Zhang
- Ziyang Zheng
- Yaoming Wang
- Wenrui Dai
- Chenglin Li
- Junni Zou
- Hongkai Xiong

author_notes:
- ""
date: "2024-03-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]


# Publication name and optional abbreviated publication name.
publication: "VCIP 2025"
publication_short: ""

abstract: "Cross-layer feature fusion critically influences the performance of deep neural networks, where mainstream approaches like additive fusion of residual connections struggle to model high-order nonlinear interactions, limiting representational capacity, while concatenative fusion of dense connections incurs significant memory and computational overhead. Although recent attention-based feature fusion methods refine feature representations and strengthen hierarchical interactions, they often struggle to balance expressiveness and efficiency. To address these limitations, we propose the Chebyshev Fusion Unit (CFU), a lightweight yet effective cross-layer fusion mechanism. Specifically, CFU computes high-order Chebyshev polynomial terms between residual features and current-layer features, each of which is aggregated through learnable scalar weights, forming enhanced fusion features. This design enables explicit modeling of complex cross-layer dependencies with minimal additional parameters. Extensive experiments across various commonly used base models on image classification, medical image segmentation, and physical law learning tasks demonstrate its superior performance."

# Summary. An optional shortened abstract.
summary: DNNs, Chebyshev Polynomials.

# tags:
# - Source Themes
featured: false


links:
# - name: Custom Link
#   url: http://example.org
url_pdf: CFU.pdf
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
