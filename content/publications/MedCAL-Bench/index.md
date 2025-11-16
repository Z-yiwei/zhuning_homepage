---
title: "MedCAL-Bench: A Comprehensive Benchmark on Cold-Start Active Learning with Foundation Models for Medical Image Analysis"
authors:
- admin
- Xiaochuan Ma
- Shaoting Zhang
- Guotai Wang

author_notes:
- "Equal contribution"
- "Equal contribution"

date: "2025-10-07T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arXiv"
# publication_short: ""

abstract: Cold-Start Active Learning (CSAL) aims to select informative samples for annotation without prior knowledge, which is important for improving annotation efficiency and model performance under a limited annotation budget in medical image analysis. Most existing CSAL methods rely on Self-Supervised Learning (SSL) on the target dataset for feature extraction, which is inefficient and limited by insufficient feature representation. Recently, pre-trained Foundation Models (FMs) have shown powerful feature extraction ability with a potential for better CSAL. However, this paradigm has been rarely investigated, with a lack of benchmarks for comparison of FMs in CSAL tasks. To this end, we propose MedCAL-Bench, the first systematic FM-based CSAL benchmark for medical image analysis. We evaluate 14 FMs and 7 CSAL strategies across 7 datasets under different annotation budgets, covering classification and segmentation tasks from diverse medical modalities. It is also the first CSAL benchmark that evaluates both the feature extraction and sample selection stages. Our experimental results reveal that：1) Most FMs are effective feature extractors for CSAL, with DINO family performing the best in segmentation; 2) The performance differences of these FMs are large in segmentation tasks, while small for classification; 3) Different sample selection strategies should be considered in CSAL on different datasets, with Active Learning by Processing Surprisal (ALPS) performing the best in segmentation while RepDiv leading for classification. The code is available at https://github.com/HiLab-git/MedCAL-Bench.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Benchmark
- Active Learning

featured: true

hugoblox:
  ids:
    arxiv: 2508.03441v2

links:
- type: pdf
  url: https://arxiv.org/pdf/2508.03441v2

- type: code
  url: https://github.com/HiLab-git/MedCAL-Bench
# - type: slides
#   url: https://www.slideshare.net/
# - type: dataset
#   url: "#"
# - type: poster
#   url: "#"
# - type: source
#   url: "#"
# - type: video
#   url: https://youtube.com
# - type: custom
#   label: Custom Link
#   url: http://example.org

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
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

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
