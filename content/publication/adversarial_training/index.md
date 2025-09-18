---
title: "Clarifying the Behavior and the Difficulty of Adversarial Training"
information: AAAI
authors:
- Xu Cheng
- Hao Zhang
- admin
- Wen Shen
- Jie Ren
- Quanshi Zhang

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2022-05-30T00:00:00Z"
doi: "https://doi.org/10.1609/aaai.v38i10.29032"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-03-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "AAAI 2024"
publication_short: ""

abstract: Adversarial training is usually difficult to optimize. This paper provides conceptual and analytic insights into the difficulty of adversarial training via a simple theoretical study, where we derive an approximate dynamics of a recursive multi-step attack in a simple setting. Despite the simplicity of our theory, it still reveals verifiable predictions about various phenomena in adversarial training under real-world settings. First, compared to vanilla training, adversarial training is more likely to boost the influence of input samples with large gradient norms in an exponential manner. Besides, adversarial training also strengthens the influence of the Hessian matrix of the loss w.r.t. network parameters, which is more likely to make network parameters oscillate and boosts the difficulty of adversarial training.

# Summary. An optional shortened abstract.
summary: Adversarial Training, ReLU Network, Hessian Matrix.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://ojs.aaai.org/index.php/AAAI/article/view/29032/29956
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
