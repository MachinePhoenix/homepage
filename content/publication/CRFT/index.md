---
title: "Enhancing Chain-of-Thought Reasoning with Critical Representation Fine-tuning"
authors:
- Chenxi Huang
- Liang Xie
- Chen Shen
- Shaotian Yan
- Sinan Fan
- admin
- Binbin Lin
- Deng Cai
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

abstract: "Representation Fine-tuning (ReFT), a recently proposed Parameter-Efficient Fine-Tuning (PEFT) method, has attracted widespread attention for significantly improving parameter efficiency by editing representation space alone. In this work, we investigate applying ReFT to complex reasoning tasks. However, directly using the native ReFT method, which modifies fixed representations at the beginning and end of each layer, yields suboptimal performance, as these fixed-position representations have uncertain impact on the outputs. We observe that, in complex reasoning tasks, there often exist certain critical representations. These representations either integrate significant information from preceding layers or regulate subsequent layer representations. Through layer-by-layer propagation, they exert a substantial influence on the final output. Naturally, fine-tuning these critical representations has the potential to greatly enhance reasoning performance. Building upon these insights, we propose \textbf{C}ritical \textbf{R}epresentation \textbf{F}ine-\textbf{T}uning (CRFT), a novel method that identifies and optimizes these critical representations through information flow analysis. CRFT operates within a supervised learning framework, dynamically optimizing critical representations in a low-rank linear subspace while freezing the base model. The effectiveness and efficiency of our method are validated across eight benchmarks for arithmetic and commonsense reasoning, using LLaMA and Mistral model families. Notably, our method improves the accuracy of LLaMA-2-7B and ReFT by 18.2 and 3.8, respectively, on GSM8K, while using only 0.016 of the model parameters, significantly less than other PEFT methods. Furthermore, our method also adapts effectively to few-shot settings, boosting one-shot accuracy by 16.4. Our work highlights the untapped potential of representation-level optimization for CoT reasoning, offering a lightweight yet powerful alternative to traditional PEFT methods."
# Summary. An optional shortened abstract.
summary: LLM, CoT, Interpretability, ReFT.

# tags:
# - Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: CRFT.pdf
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
