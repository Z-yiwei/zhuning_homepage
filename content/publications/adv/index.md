---
title: "Adversarial Frequency Component Reconstruction Constraint for Helicopter Vibration Signal Anomaly Detection: An Unsupervised Dual-Domain Approach"

authors:
- admin
- Tianzhi Xu Dong
- Dandan Peng

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2025-09-01T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*IEEE Transactions on Instrumentation and Measurement*"
publication_short: "*IEEE TIM*"

abstract: Vibration signal anomaly detection plays a vital role in predictive maintenance and fault diagnosis of helicopters. While deep learning-driven approaches that combine both time- and frequency-domain methods hold potential for anomaly detection, existing work on helicopter vibration signals remains limited. To this end, we propose TransGANomaly, an unsupervised dual-domain Gated-Transformer network based on adversarial frequency component reconstruction constraints for detecting anomalies in helicopter vibration signals. We construct a tri-branch adversarial training framework, employing the Transformer architecture to extract frequency-domain features and encode time-domain correlations. This enables the model to learn and reconstruct the original frequency-domain amplitude, phase information, and raw time-domain data of normal patterns. To enhance the sensitivity and robustness of adversarial training, we also introduce a novel embedding space constraint, which encourages the model to learn an optimal latent representation. We provide theoretical proof of the embedding constraint’s effectiveness in anomaly detection based on the manifold hypothesis and the maximum evidence lower bound (ELBO). Experiments on real-world helicopter vibration data demonstrate that the proposed model achieves an area under the curve (AUC) of 0.989 and an F1-score of 0.974, outperforming all state-of-the-art baselines.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Anomaly Detection
featured: true

hugoblox:
  ids:
    doi: 10.1109/TIM.2025.3591867

links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11102127
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
