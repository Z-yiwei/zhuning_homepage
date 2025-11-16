---
title: 'High-order Flow Matching: Unified Framework and Sharp Statistical Rates'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Maojiang Su
  - Jerry Yao-Chieh Hu
  - Yi-Chen Lee
  - admin
  - Jui-Hui Chung
  - Shang Wu
  - Zhao Song
  - Minshuo Chen
  - Han Liu

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - 'Equal contribution'

date: '2025-07-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *39th Annual Conference on Neural Information Processing Systems*
publication_short: In *NeurIPS 2025*

abstract: Flow matching is an emerging generative modeling framework that learns continuous-time dynamics to map noise into data. To enhance expressiveness and sampling efficiency, recent works have explored incorporating high-order trajectory information. Despite the empirical success, a holistic theoretical foundation is still lacking. We present a unified framework for standard and high-order flow matching that incorporates trajectory derivatives up to an arbitrary order \( K \). Our key innovation is establishing the marginalization technique that converts the intractable \( K \)-order loss into a simple conditional regression with exact gradients and identifying the consistency constraint. We establish sharp statistical rates of the \( K \)-order flow matching implemented with transformer networks. With \( n \) samples, flow matching estimates nonparametric distributions at a rate \( \hat{\tilde{O}}(n^{-\Theta(1/d)}) \), matching minimax lower bounds up to logarithmic factors.

# Summary. An optional shortened abstract
# summary: 

tags:
  - Machine Learning

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
# hugoblox:
#   ids:
#     doi: 10.1007/978-3-032-04937-7_12

# Custom links
links:
  - type: pdf
    url: "https://openreview.net/forum?id=ib0aV2hphN"
  # - type: code
  #   url: https://github.com/HiLab-git/CSAL-3D
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
