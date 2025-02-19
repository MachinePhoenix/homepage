---
title: "RST: Residual Side Tuning with Cross-Layer Correlation for Parameter Efficient Transfer Learning"
authors:
- admin
- - Yaoming Wang
- Jiarui Zhang
- - Wenrui Dai
- Ziyang Zheng
- Chenglin Li
- Junni Zou
- Hongkai Xiong

author_notes:
- ""
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

abstract: Existing fine-tuning methods for pre-trained models, including parameter-efficient transfer learning (PETL) approaches, suffer from inefficient information extraction and substantial resource consumption. To address these issues, we present Residual Side Tuning (RST), a novel PETL framework designed to enhance information extraction efficiency while maintaining minimal additional parameters. Specifically, RST extracts aggregated features, i.e., residuals, and employs a dual-block side tuning structure: Collect Blocks extract inter-layer information into residuals while Feed Blocks strategically reintegrate them back into the backbone. This parallel processing framework effectively models cross-layer relationships and significantly improves the efficiency of hierarchical feature extraction. Furthermore, RST reinforces these relationships by leveraging an element-wise feature enhancement strategy that integrates residuals with the current layer’s outputs, thereby augmenting information extraction capabilities. This enhanced extraction efficiency enables a parameter sharing strategy within the Collect Blocks, significantly reducing the number of trainable parameters through shared adaptations across multiple layers. Extensive experiments on several benchmark datasets, particularly in low-shot learning scenarios, demonstrate that RST not only outperforms existing PETL methods in accuracy but also achieves substantial reductions in both parameter and memory usage.
# Summary. An optional shortened abstract.
summary: PETL, side-tuning, ViT.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: 
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
