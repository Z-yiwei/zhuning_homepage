---
title: "An Adversarial Training Framework Based on Unsupervised Feature Reconstruction Constraints for Crystalline Silicon Solar Cells Anomaly Detection"

authors:
- admin
- Jing Wang
- Ying Zhang
- Huan Wang
- Te Han

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Instrumentation and Measurement *"
publication_short: "*IEEE TIM*"

abstract: Photovoltaic (PV) power generation has risen prominently across the globe. However, the functioning of PV systems can be substantially diminished by defective solar cells. Electroluminescence (EL) imaging has emerged as an effective tool for identifying such defects. In this article, inspired by the manifold hypothesis, we propose a novel unsupervised adversarial training framework based on feature reconstruction constraints in different spaces for crystalline silicon solar cell anomaly detection. Adversarial constraints are specially designed for both original high-dimensional image space and latent low-dimensional representational space. The adversarial training strategy aims to seek the optimal latent representation of normal data. By minimizing the distance between images and between latent representations, it can not only generate similar images but achieve good latent reconstruction performance. We also employ Gaussian Context Transformer (GCT) to enhance better long-range semantic dependency with less computational complexity. During testing, poor feature reconstruction of either a high-dimension image or a low-dimension latent vector indicates a potential anomaly. Although the proposed framework does not use labeled data for training, it can distinguish out-of-domain defect samples from in-domain normal samples and identify small defects that may not be discernible using other methods. Experimental results over real-life EL datasets demonstrate that theframework achieves satisfactory performance by outperformining other machine learning or deep-learning-driven methods. It offersa resilient solution for defect detection in crystalline silicon solar cells within the industry, bridging the gap of unsupervised approaches in this industrial domain.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: true

hugoblox:
  ids:
    doi: 10.1109/TIM.2024.3462989

links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10683727
  - type: code
    url: https://github.com/Z-yiwei/AUFRC


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
