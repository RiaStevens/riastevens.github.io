---
title: 'Optimal Prediction-Augmented Algorithms for Testing Independence of Distributions'

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Maryam Aliakbarpour
  - Alireza Azizi
  - me

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-03-04T00:00:00Z'

# Schedule page publish date (NOT publication's date).
# publishDate: '2025-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: To appear at the *Thirty-Ninth Annual Conference on Learning Theory (COLT 2025)*
publication_short: To appear at *COLT 2026*

abstract: Independence testing is a fundamental problem in statistical inference. Given samples from a joint distribution $p$ over multiple random variables, the goal is to determine whether $p$ is a product distribution or is $\epsilon$-far from all product distributions in total variation distance. In the non-parametric finite-sample regime, this task is notoriously expensive, as the minimax sample complexity scales polynomially with the support size. In this work, we move beyond these worst-case limitations by leveraging the framework of \textit{augmented distribution testing}. We design independence testers that incorporate auxiliary, but potentially untrustworthy, predictive information. Our framework ensures that the tester remains robust, maintaining worst-case validity regardless of the prediction's quality, while significantly improving sample efficiency when the prediction is accurate. Our main contributions include (i) a bivariate independence tester for discrete distributions that adaptively reduces sample complexity based on the prediction error; (ii) a generalization to the high-dimensional multivariate setting for testing the independence of $d$ random variables; and (iii) matching minimax lower bounds demonstrating that our testers achieve optimal sample complexity.

draft: false
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Independence Testing
  - Augmented Algorithms

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    arxiv: 2603.04635

# Custom links
links:
  - type: pdf
    url: "indTest-paper.pdf"
  # - type: slides
  #   url: https://neurips.cc/virtual/2025/loc/mexico-city/poster/118634
  # - type: poster
  #   url: https://neurips.cc/media/PosterPDFs/NeurIPS%202025/118634.png?t=1764133151.245049

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
