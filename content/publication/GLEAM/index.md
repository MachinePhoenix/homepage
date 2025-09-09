---
title: "GLEAM: Global Share Local Transform MoE for Downstream Transferring With Enhanced Parameter Efficiency"
authors:
- Jiarui Zhang
- admin
- Yaoming Wang
- Wenrui Dai
- Ziyang Zheng
- Chenglin Li
- Junni Zou
- Hongkai Xiong

author_notes:
- ""
date: "2024-08-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "ECAI 2025"
publication_short: ""

abstract: Parameter-efficient transfer learning (PETL) has emerged as a promising direction to fine-tune lightweight modules and adapt large-scale pre-trained models to downstream tasks. Nevertheless, these methods have not thoroughly explored the characteristics of PETL methods to optimize the fine-tuning performance with miminal volume of parameters. In this paper, we first reveal that, compared to pre-trained models, PETL tends to generate similar features via homogeneous feature transformations across different layers. Subsequently, we propose a Global Sharing Local Transformation framework, namely Gleam that decomposes the adapter into a shared component and layer-specific local components to simultaneously reduce the redundancy in layer-wise parameter matrices for homogeneous feature transformations and fine-tune the locally specific parameters for minimizing performance loss. Speficially, we develop a shared mixture of convolution that introduces shared multi-scale sparse MoE to enable diverse transformations for suppressing the homogeneity issue of feature transformations in PETL. To accurately evaluate Gleam, we test it on more than 20 datasets for image classification and few-shot learning performance. Experimental results demonstrate that the proposed method performs on par with existing PETL methods like LoRA with only 3% of its parameters and further yields competitive performance using only 0.07M parameters.

# Summary. An optional shortened abstract.
summary: PETL, Transformer, LoRA.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: GLEAM.pdf
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
