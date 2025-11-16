---
title: 'An example conference paper'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - test

# Author notes (optional)
author_notes:
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
publication: In *28th International Conference on Medical Image Computing and Computer Assisted Intervention*
publication_short: In *MICCAI 2025*

abstract: Active Learning (AL) is a promising solution in medical image segmentation to reduce annotation costs by selecting the most informative training samples. However, traditional warm-start AL methods rely on iterative querying and fail to address the cold-start dilemma. While Cold-Start Active Learning (CSAL) attempts to resolve this, current methods are limited to 2D images and neglect Self-Supervised Learning (SSL)’s potential for uncertainty estimation in AL. Moreover, while hybrid uncertainty-diversity sampling has been discussed in warm-start setting, the efficacy of this combined approach is not explored in CSAL. In this paper, we present CSAL-3D: a novel Cold-Start Active Learning framework for 3D medical image segmentation. Firstly, a CSAL-adapted SSL pipeline for ensemble-based uncertainty estimation and 3D-oriented feature extraction is proposed. Secondly, a novel Uncertainty-Reinforced Diversity Sampling (URDS) strategy is introduced, which synthesizes cluster representativeness and sample-level uncertainty in a hierarchical process. It can select samples that are both uncertain and representative in one shot. Experiments on Brain Tumor, Heart and Spleen organ segmentation tasks from CT or MRI 3D images show that CSAL-3D outperforms other state-of-the-art CSAL counterparts with an avergae Dice of 87.03%. The source code is available at https://github.com/HiLab-git/CSAL-3D.

Summary. An optional shortened abstract.
summary: Active Learning (AL) is a promising solution in medical image segmentation to reduce annotation costs by selecting the most informative training samples. However, traditional warm-start AL methods rely on iterative querying and fail to address the cold-start dilemma. While Cold-Start Active Learning (CSAL) attempts to resolve this, current methods are limited to 2D images and neglect Self-Supervised Learning (SSL)’s potential for uncertainty estimation in AL. Moreover, while hybrid uncertainty-diversity sampling has been discussed in warm-start setting, the efficacy of this combined approach is not explored in CSAL. In this paper, we present CSAL-3D: a novel Cold-Start Active Learning framework for 3D medical image segmentation. Firstly, a CSAL-adapted SSL pipeline for ensemble-based uncertainty estimation and 3D-oriented feature extraction is proposed. Secondly, a novel Uncertainty-Reinforced Diversity Sampling (URDS) strategy is introduced, which synthesizes cluster representativeness and sample-level uncertainty in a hierarchical process. It can select samples that are both uncertain and representative in one shot. Experiments on Brain Tumor, Heart and Spleen organ segmentation tasks from CT or MRI 3D images show that CSAL-3D outperforms other state-of-the-art CSAL counterparts with an avergae Dice of 87.03%.

tags:
  - Active Learning
  - Medical Image Analysis

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.5555/123456

# Custom links
links:
  - type: pdf
    url: "https://papers.miccai.org/miccai-2025/paper/2315_paper.pdf"
  - type: code
    url: https://github.com/HiLab-git/CSAL-3D
  - type: dataset
    url: http://medicaldecathlon.com/
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
