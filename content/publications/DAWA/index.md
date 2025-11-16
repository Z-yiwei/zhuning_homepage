---
title: "Deep adaptive wavelet autoencoder with mutually independent empirical cumulative distribution for unsupervised motor anomaly detection"

authors:
- Pinze Ren
- admin
- Dandan Peng
- Liyuan Ren
- Huan Wang

author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Engineering Applications of Artificial Intelligence*"
publication_short: "*EAAI*"

abstract: Permanent magnet synchronous motors (PMSMs) are widely used in industrial applications but remain vulnerable to stator faults, such as inter-coil and inter-turn short circuits. Although recent deep learning-based fault detection methods have shown promise, they typically rely on large volumes of labelled fault data for training. To address this limitation, this paper proposes a novel unsupervised fault detection framework, termed Deep Adaptive Wavelet Autoencoder (DAWA) with Mutually Independent Empirical Cumulative Distribution (MIECD), specifically designed for PMSM fault detection. DAWA utilizes convolutional neural networks to learn adaptive wavelet filters through fast discrete wavelet transform, allowing for fully learnable, threshold-free extraction of fine-grained signal patterns. The resulting latent features are then mapped by MIECD into a mutually independent space via independent component analysis (ICA). Without assuming any prior data distribution, MIECD estimates empirical cumulative distributions (ECDs), computes tail probabilities across dimensions, and aggregates them into a unified anomaly score. Experimental results on motor vibration datasets demonstrate the effectiveness of the proposed method, showing average accuracy improvements of 15.85 % for Interturn and 15.16 % for Intercoil fault detection compared to conventional data-driven baselines across various operating conditions.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

hugoblox:
  ids:
    doi: 10.1016/j.engappai.2025.112446

links:
  - type: pdf
    url: https://www.sciencedirect.com/science/article/pii/S0952197625024777
  # - type: code
  #   url: https://github.com/Z-yiwei/AUFRC


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
