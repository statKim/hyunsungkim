---
title: "Conformal Outlier Detection for Multivariate Functional Data"
authors:
- admin
- Junyong Park
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2026-06-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-09-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Computational Statistics*, 41(4), 88"
publication_short: ""

abstract: Detecting outliers in multivariate functional data is crucial in a range of applications, including biomedical signal analysis and environmental monitoring. Existing methods primarily focus on identifying outliers within a given dataset but lack a principled approach for determining whether newly observed functional data deviate from a reference population. To address this limitation, we extend the conformal outlier detection framework of Bates et al. (2023) to the multivariate functional setting. A key challenge in this extension is defining appropriate nonconformity scores that effectively capture the structure of multivariate functional observations. We propose a novel nonconformity score based on the multivariate functional depth measure, which assess the centrality of an observation within a functional data distribution. This approach ensures the false discovery rate (FDR) control while offering a flexible, distribution-free method for functional outlier detection. We further introduce two practical enhancements; (i) leveraging curve transformations to improve the detection of shape outliers, and (ii) developing a two-step procedure to handle mixed training sets where the reference data may already contain outliers. The effectiveness of the proposed method is demonstrated through simulation studies and a real-data application using fMRI signals from the ADHD-200 dataset.

# Summary. An optional shortened abstract.
summary: 

tags:
- Conformal inference
- Outlier detection
- Multivariate functional data
- Functional depth
- Multiple testing
- False discovery rate
featured: false

# links:
url_pdf: https://doi.org/10.1007/s00180-026-01763-1
url_code: 'https://github.com/statKim/foutlier_cp'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# # Featured image
# # To use, add an image named `featured.jpg/png` to your page's folder. 
#   image:
#     caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#     focal_point: ""
#     preview_only: false

# # Associated Projects (optional).
# #   Associate this publication with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `internal-project` references `content/project/internal-project/index.md`.
# #   Otherwise, set `projects: []`.
# projects:
# - internal-project

# # Slides (optional).
# #   Associate this publication with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides: "example"` references `content/slides/example/index.md`.
# #   Otherwise, set `slides: ""`.
# slides: example
---

<!--
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
-->
