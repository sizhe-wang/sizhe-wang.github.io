---
title: "ScaleADFG: Affordance-based Dexterous Functional Grasping via Scalable Dataset"
authors:
- Wei Wei
- Peng Wang
- admin
- Yongkang Luo
- Wanyi Li
- Daheng Li
- Yayu Huang
- Haonan Duan

date: "2024-06-28T00:00:00Z"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-10-24T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Transactions on Robotics"
publication_short: "T-RO"

abstract: This article investigates the challenge of enabling multi-finger hands to perform human-like functional grasping for various intentions. However, accomplishing functional grasping in real robot hands present many challenges, including handling generalization ability for kinematically diverse robot hands, generating intention-conditioned grasps for a large variety of objects, and incomplete perception from a single-view camera. In this work, we first propose a six-step functional grasp synthesis algorithm based on fine-grained contact modeling. With the fine-grained contact-based optimization and learned dense shape correspondence, the algorithm is adaptable to various objects of the same category and a wide range of multi-finger hands using few demonstrations. Secondly, over 10K functional grasps are synthesized to train our neural network, named DexFG-Net, which generates intention-conditioned grasps based on reconstructed object. Extensive experiments in the simulation and physical grasps indicate that the grasp synthesis algorithm can produce human-like functional grasp with robust stability and  functionality, and the DexFG-Net can generate plausible and human-like intention-conditioned grasping postures for anthropomorphic hands. Project page and video demonstration is available at [https://v-wewei.github.io/sr_dexgrasp](https://v-wewei.github.io/sr\_dexgrasp).

# Summary. An optional shortened abstract.
summary:  Our work **DexFG** integrates fine-grained contact modeling and intention-conditioned learning to achieve generalizable, human-like functional grasping with diverse robot hands.

tags:
- Dexterous Functional Grasping

featured: true

hugoblox:
  ids:
    arxiv: 2303.17808

links:
- type: preprint
  provider: arxiv
  id: 2303.17808
# - type: code
#   url: https://github.com/HugoBlox/hugo-blox-builder
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
  label: Project Page
  url: https://v-wewei.github.io/sr_dexgrasp

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
projects: []
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publications/conference-paper/) on LLMs.

> [!NOTE]
> Create your slides in Markdown - click the *Slides* button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
