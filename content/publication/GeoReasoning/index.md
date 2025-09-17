---
title: "Generalizable Geometric Image Caption Synthesis"
authors:
- admin
- Wenyuan Wang
- Rui Pan
- Howard Meng
- Renjie Pi
- Ruida Wang
- Tong Zhang

author_notes:
- ""
date: "2025-05-16T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]


# Publication name and optional abbreviated publication name.
publication: "NeurIPS 2025"
publication_short: ""

abstract: "Multimodal large language models have various practical applications that demand strong reasoning abilities. Despite recent advancements in this area, these models still struggle to solve complex geometric problems. A key challenge stems from the lack of high-quality image-text pair datasets for understanding geometric images. Furthermore, most template-based data synthesis pipelines typically fail to generalize to questions outside their predefined templates. In this paper, we mitigate this issue by introducing a complementary RLHF process into the data generation pipeline. By adopting RAFT to adjust captions for image-text pairs generated from fewer than 50 templates and using reward signals derived from downstream mathematical problem-solving tasks, our pipeline successfully captures the key features of geometry problem-solving. This enables better task generalization and yields non-trivial improvements. Furthermore, the generated dataset also enhances the general mathematical reasoning capabilities of multimodal large language models beyond the domain of geometric mathematical problems, yielding accuracy improvements of 2.8%–5.3% in arithmetic, algebraic, and numerical tasks with even non-geometric input images."

# Summary. An optional shortened abstract.
summary: MLLM, Data Generation, Geometry, RLVR.

# tags:
# - Source Themes
featured: false


links:
# - name: Custom Link
# url: 
url_pdf: GeoReasoning.pdf
url_code: 'https://github.com/MachinePhoenix/GeoReasoning'
url_dataset: 'https://huggingface.co/datasets/ScaleMath/GeoReasoning'
# url_poster: ''
url_project: 'https://machinephoenix.github.io/GeoReasoning_blog/'
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
