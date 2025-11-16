---
title: "Unsupervised Anomaly Detection for Aircraft PRSOV With Random Projection-Based Inner Product Prediction"

authors:
- Dandan Peng
- admin
- Te Han
- Zhuyun Chen
- Chenyu Liu

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
publication: "*IEEE Transactions on Instrumentation and Measurement*"
publication_short: "*IEEE TIM*"

abstract: Pressure-regulated shutoff valves (PRSOVs) are critical components of aircrafts’ environmental control system (ECS) to regulate the carbon pressure, ensuring it within a safe and comfortable range. However, due to the harsh and dynamic operational environment, PRSOVs are susceptible to various anomalies, which may lead to severe flight incidents such as cabin depressurization. To this end, this article proposed an unsupervised anomaly detection approach for PRSOV with random projection-based inner product prediction (RPDP-AD). It leverages distance information in a randomly projected space to construct supervisory signals. This enables our model to encode distribution patterns and data structures of normal samples from unlabeled data. Our model is optimized to minimize the prediction errors in the random projection space. We introduced a distribution difference metric to minimize the discrepancy between learnable mappings and random mappings in low-dimensional space. Anomalous samples will have greater distribution differences, which allow for unsupervised anomaly detection (UAD). This article explored the connection between neural networks and random projection theory for industrial anomaly detection. To further support its effectiveness, we also provide a theoretical analysis of inner product preservation property via Johnson–Lindenstrauss theorem. Experiments were conducted on a PRSOV dataset including seven types of anomalies with different random projection methods. Results demonstrate that our method outperforms other data-driven counterparts. Our source code will be available at https://github.com/Z-yiwei/RPDP-AD

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

hugoblox:
  ids:
    doi: 10.1109/TIM.2024.3462989

links:
  - type: pdf
    url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=11006485
  - type: code
    url: https://github.com/Z-yiwei/RPDP-AD


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
