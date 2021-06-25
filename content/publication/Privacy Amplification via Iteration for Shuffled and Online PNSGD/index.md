---
title: "Privacy Amplification via Iteration for Shuffled and Online PNSGD"
authors:
- admin
- Zhiqi Bu
- Jinshuo Dong
date: "2021-01-01"
#doi: "10.1016/j.spl.2019.06.010"

# Schedule page publish date (NOT publication's date).
#publishDate: "2019-06-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *European Conference on Machine Learning*
publication_short: ""

abstract: "In this paper, we consider the framework of privacy amplification via iteration, which is originally proposed by Feldman et al. and subsequently simplified by Asoodeh et al. in their analysis via the contraction coefficient. This line of work focuses on the study of the privacy guarantees obtained by the projected noisy stochastic gradient descent (PNSGD) algorithm with hidden intermediate updates. A limitation in the existing literature is that only the early stopped PNSGD has been studied, while no result has been proved on the more widely-used PNSGD applied on a shuffled dataset. Moreover, no scheme has been yet proposed regarding how to decrease the injected noise when new data are received in an online fashion. In this work, we first prove a privacy guarantee for shuffled PNSGD, which is investigated asymptotically when the noise is fixed for each sample size n but reduced at a predetermined rate when n increases, in order to achieve the convergence of privacy loss. We then analyze the online setting and provide a faster decaying scheme for the magnitude of the injected noise that also guarantees the convergence of privacy loss."

# Summary. An optional shortened abstract.
# summary: 

#tags:
#- Source Themes
#featured: true

links:
url_pdf: "https://arxiv.org/pdf/2106.11767.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image: 
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: ""

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---
