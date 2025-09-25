---
title: "Serpent: Scalable and Efficient Image Restoration via Multi-scale Structured State Space Models"
authors:
- admin
- Zalan Fabian
- Mahdi Soltanolkotabi
date: "2024-03-26T00:00:00Z"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Next Generation of Sequence Modeling Architectures Workshop @ ICML (2024)"
publication_short: "NGSM @ ICML"

abstract: The landscape of computational building blocks of efficient image restoration architectures is dominated by a combination of convolutional processing and various attention mechanisms. However, convolutional filters, while efficient, are inherently local and therefore struggle with modeling long-range dependencies in images. In contrast, attention excels at capturing global interactions between arbitrary image regions, but suffers from a quadratic cost in image dimension. In this work, we propose Serpent, an efficient architecture for high-resolution image restoration that combines recent advances in state space models (SSMs) with multi-scale signal processing in its core computational block. SSMs, originally introduced for sequence modeling, can maintain a global receptive field with a favorable linear scaling in input size. We propose a novel hierarchical architecture inspired by traditional signal processing principles, that converts the input image into a collection of sequences and processes them in a multi-scale fashion. Our experimental results demonstrate that Serpent can achieve reconstruction quality on par with state-of-the-art techniques, while requiring orders of magnitude less compute (up to 150 fold reduction in FLOPS) and a factor of up to 5× less GPU memory while maintaining a compact model size. The efficiency gains achieved by Serpent are especially notable at high image resolutions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Image restoration
- State space models
- Efficient architectures

featured: false

hugoblox:
  ids:
    arxiv: 2403.17902

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

