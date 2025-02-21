---
title: "Bootstrap Prompt Learning with Feature Adaptation for Vision-Language Efficient Tuning"
authors:
- Jiarui Zhang
- Yaoming Wang
- admin
- Wenrui Dai

- Chenglin Li
- Junni Zou
- Hongkai Xiong

author_notes:
date: "2025-02-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "ICML 2025"
publication_short: ""

abstract: "As popular alternatives to fine-tune vision-language foundation models such as CLIP, prompt learning and adapter tuning resort to pre-adjustment in the input space and post-adjustment on the pretrained weight matrices to optimize the task-specific objective, respectively. However, there still lacks a method to jointly exploit their benefits due to potential conflicts in optimization directions. In this paper, we propose a novel framework named adaPter bootstrApped prompt contrastive Tuning (PAT) to address this problem. Specifically, we bootstrap prompt learning with adapters and achieves pre-post alignment to avoid mismatch between the optimization directions of prompter learning and adapter tuning. Furthermore, we propose a tolerance regularization that equally pushes away all negative samples and improves generalization by introducing additional categories of unlabeled data to avoid overfitting. To our best knowledge, this is the first successful attempt to simultaneously exploit the advantages of prompt learning and adapter tuning. Extensive evaluations demonstrate that PAT achieves state-of-the-art performance in various recognition tasks on three prevailing benchmarks."
# Summary. An optional shortened abstract.
summary: Vision language model, PETL, ViT.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: PAT.pdf
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
