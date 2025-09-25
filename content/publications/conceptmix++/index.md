---
title: "ConceptMix++: Leveling the Playing Field in Text-to-Image Benchmarking via Iterative Prompt Optimization"
authors:
- Haosheng Gan
- Berk Tinaz
- Mohammad Shahab Sepehri
- Zalan Fabian
- Mahdi Soltanolkotabi


date: "2025-05-26T00:00:00Z"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "3rd Workshop on Generative Models for Computer Vision @ CVPR (2025)"
publication_short: "GMCV @ ICML"

abstract: Current text-to-image (T2I) benchmarks evaluate models on rigid prompts, potentially underestimating true generative capabilities due to prompt sensitivity and creating biases that favor certain models while disadvantaging others. We introduce ConceptMix++, a framework that disentangles prompt phrasing from visual generation capabilities by applying iterative prompt optimization. Building on ConceptMix, our approach incorporates a multimodal optimization pipeline that leverages vision-language model feedback to refine prompts systematically. Through extensive experiments across multiple diffusion models, we show that optimized prompts significantly improve compositional generation performance, revealing previously hidden model capabilities and enabling fairer comparisons across T2I models. Our analysis reveals that certain visual concepts -- such as spatial relationships and shapes -- benefit more from optimization than others, suggesting that existing benchmarks systematically underestimate model performance in these categories. Additionally, we find strong cross-model transferability of optimized prompts, indicating shared preferences for effective prompt phrasing across models. These findings demonstrate that rigid benchmarking approaches may significantly underrepresent true model capabilities, while our framework provides more accurate assessment and insights for future development.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Diffusion Model
- Generative AI
- Prompt Optimization

featured: false

hugoblox:
  ids:
    arxiv: 2507.03275

links:
- type: code
  url: https://github.com/MShahabSepehri/Serpent

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
# slides: ""
---

