---
title: 'SUGFW: A SAM-Based Uncertainty-Guided Feature Weighting Framework for Cold Start Active Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
  - Xiaochuan Ma
  - Jia Fu
  - Lanfeng Zhong
  - admin
  - Guotai Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-10-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *28th International Conference on Medical Image Computing and Computer Assisted Intervention*
publication_short: In *MICCAI 2025*

abstract: In medical image segmentation, manual annotation is an exceptionally costly process, highlighting the critical need for selecting the most valuable samples for labeling. Active learning provides an effective solution for selecting informative samples, however, they face the challenge of cold start, where the initial training samples are randomly chosen, potentially leading to suboptimal model performance. In this study, we present a novel cold start active learning framework based on Segment Anything Model (SAM), which leverages the zero-shot capabilities of SAM on downstream datasets to address the cold start issue effectively. Concretely, we employ a multiple augmentation strategy to estimate the uncertainty map for each case, then calculate patch-level uncertainty corresponding to the patch-level features generated from SAM’s image encoder. Then we propose a Patch-based Global Distinct Representation (PGDR) strategy that integrates patch-level uncertainty and image features into a unified image-level representation. To select the samples with representative and diverse information, we propose a Greedy Selection with Cluster and Uncertainty (GSCU) strategy, which effectively combines the image-level features and uncertainty to prioritize samples for manual annotation. Experiments on prostate and left atrium segmentation datasets demonstrate that our framework outperforms five state-of-the-art methods as well as random selection in various selection ratios. For both datasets, our method achieves comparable performance to that of the fully-supervised method with only 10% and 1.5% annotation burden. Code is available at https://github.com/Hilab-git/SUGFW.git.

# Summary. An optional shortened abstract
# summary: 

tags:
  - Active Learning
  - Medical Image Analysis

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-032-04937-7_55

# Custom links
links:
  - type: pdf
    url: "https://papers.miccai.org/miccai-2025/paper/1739_paper.pdf"
  - type: code
    url: https://github.com/Hilab-git/SUGFW.git.
  # - type: dataset
  #   url: http://medicaldecathlon.com/
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example. -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
