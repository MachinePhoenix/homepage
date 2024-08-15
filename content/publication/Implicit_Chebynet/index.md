---
title: "ICPNet: A Network of Network with Implicit Layers and Chebyshev Polynomial Activation Function"
authors:
- admin
- Jiarui Zhang
- Wen Fei
- Ziyang Zheng
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
publication: "NeurIPS 2024"
publication_short: ""

abstract: Deep neural networks (DNNs) have become great techniques to solve optimization problems in almost every area. However, the architectures of deep networks are highly diverse, and the design and selection of structures often rely on empirical knowledge. In response, this paper proposes ICPNet, a unified model capable of representing networks with arbitrary depths and any activation function by fitting a certain network. Specifically, ICPNet employs Chebyshev polynomials to approximate a specific activation function as the network's activation function and constructs fixed-point iteration layers to approximate networks with arbitrary depths. Then we verify two great properties of ICPNet. First, the learning and representation ability of ICPNet is stronger than that of the approximated model. Besides, the cosine similarity between the optimization direction of conventional blocks and their corresponding fixed-point blocks is closely related to the training of the network, based on which a regularization term is designed for optimizing the network. It's verified that the term improves the learning ability even when incorporated into the original network alone. Various experiments across multiple tasks are conducted to verify the efficacy of ICPNet or even the plug-and-play module without incurring additional memory overhead. The source code will be submitted to github if accepted.

# Summary. An optional shortened abstract.
summary: Chebyshev Polynomials, Deep Equilibrium Model.

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
