---
title: 'Nearly-Linear Time Private Hypothesis Selection with the Optimal Approximation Factor'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Maryam Aliakbarpour
  - Zhan Shi
  - me
  - Vincent X. Wang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-06-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In the *Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)*
publication_short: In *NeurIPS 2025*

abstract: Estimating the density of a distribution from its samples is a fundamental problem in statistics. Hypothesis selection addresses the setting where, in addition to a sample set, we are given n candidate distributions-referred to as hypotheses-and the goal is to determine which one best describes the underlying data distribution. This problem is known to be solvable very efficiently, requiring roughly $O(\log n)$ samples and running in $\tilde{O}(n)$ time. The quality of the output is measured via the total variation distance to the unknown distribution, and the approximation factor of the algorithm determines how large this distance is compared to the optimal distance achieved by the best candidate hypothesis. It is known that $\alpha=3$ is the optimal approximation factor for this problem. We study hypothesis selection under the constraint of differential privacy. We propose a differentially private algorithm in the central model that runs in nearly-linear time with respect to the number of hypotheses, achieves the optimal approximation factor, and incurs only a modest increase in sample complexity, which remains polylogarithmic in $n$. This resolves an open question posed by [Bun, Kamath, Steinke, Wu, NeurIPS 2019]. Prior to our work, existing upper bounds required quadratic time.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Differential Privacy
  - Hypothesis Selection

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2506.01162

# Custom links
links:
  - type: pdf
    url: "hypSel-paper.pdf"
  - type: slides
    url: https://neurips.cc/virtual/2025/loc/mexico-city/poster/118634
  - type: poster
    url: https://neurips.cc/media/PosterPDFs/NeurIPS%202025/118634.png?t=1764133151.245049

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example.

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
