---
title: "SalaMAnder: Shapley-based Mathematical Expression Attribution and Metric for Chain-of-Thought Reasoning"
authors:
- admin
- Chen Shen
- Shaotian Yan
- Yaoming Wang
- Xiaosong Yuan
- Chenxi Huang
- Jieping Ye

author_notes:

date: "2025-02-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "ACL 2025"
publication_short: ""

abstract: "While chain-of-thought (CoT) prompting has demonstrated remarkable efficacy in enhancing the reasoning capacities of large language models (LLMs) for mathematical problem-solving, the mechanistic foundations underlying these improvements remain inadequately characterized and lack systematic theoretical investigation. In this paper, we present \textbf{SalaMAnder} (\textbf{S}h\textbf{a}p\textbf{l}ey-b\textbf{a}sed \textbf{M}athematical Expression \textbf{A}ttribution a\textbf{nd} M\textbf{e}t\textbf{r}ic), a theoretically grounded methodology as well as a mathematically rigorous evaluation metric for quantifying component-level contributions in CoT reasoning. Specifically, we leverage Shapley value for mathematical expression attribution and develop an efficient stratified sampling algorithm that significantly reduces the computational complexity. Besides, we develop the \textbf{CoSP} (\textbf{C}ardinality \textbf{o}f \textbf{S}hapley \textbf{P}ositives) metric through covariance analysis. Comprehensive validation across multiple LLM models and diverse mathematical benchmarks demonstrate that the CoSP metric within our SalaMAnder framework exhibits a robust monotonic correlation with model performance. This correlation not only provides theoretical explanations for the empirical success of existing CoT but also establishes mathematically rigorous principles for prompt construction optimization. Finally, the analytical capabilities of SalaMAnder is further substantiated by performance improvements achieved through targeted refinement of low-CoSP components, demonstrating both the explanatory power and practical utility in understanding and enhancing CoT reasoning."

# Summary. An optional shortened abstract.
summary: LLM, CoT, Interpretability, Shapley Value.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: SalaMAnder.pdf
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
