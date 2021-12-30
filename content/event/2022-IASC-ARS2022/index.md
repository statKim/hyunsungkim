---
title: Robust principal component analysis applicable to partially observed functional data

event: The 11th Conference of the IASC-ARS (The Asian Regional Section of the International Association for Statistical Computing)
event_url: https://iasc-ars2022.org/

location: Doshisha University (Hybrid conference)
address:
  # street: 450 Serra Mall
  city: Kyoto
  region: Japan
  # postcode: '94305'
  # country: Japan

summary: IASC-ARS2022
abstract: "In recent years, applications have emerged that produce partially observed functional data, where each trajectory is collected over individual-specific subinterval(s) within the whole domain of interest. Robustness to atypical partially observed curves in the application is a practical concern, especially in the dimension reduction step through functional principal component analysis (FPCA). Existing studies implemented FPCA by applying smoothing techniques to estimate mean and covariance functions under irregular functional data structure, however, its estimation is easily affected by outlying curves with heavy-tailed noises or spikes. In this study, we investigate the robust method for the mean and covariance estimations by using bounded loss function, and it enables us to obtain robust functional principal components under partially observed functional data. Using the functional principal scores, we reconstruct the missing parts of trajectories. Numerical experiments show that our method provides a stable and robust estimation when the data contain the atypical curves."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-02-23T14:00:00Z"
date_end: "2022-02-23T15:20:00Z"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2022-02-23T00:00:00Z"

authors: [Hyunsung Kim]
tags: [partially observed functional data, covariance estimation, principal component analysis, robustness]

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: "uploads/"
url_video: ""

# # Markdown Slides (optional).
# #   Associate this talk with Markdown slides.
# #   Simply enter your slide deck's filename without extension.
# #   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
# #   Otherwise, set `slides = ""`.
# slides: example

# # Projects (optional).
# #   Associate this post with one or more of your projects.
# #   Simply enter your project's folder or file name without extension.
# #   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
# #   Otherwise, set `projects = []`.
# projects:
# - internal-project
---

<!--
{{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page.
-->
