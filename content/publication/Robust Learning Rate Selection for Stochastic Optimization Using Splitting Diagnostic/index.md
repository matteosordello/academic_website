---
title: "Robust Learning Rate Selection for Stochastic Optimization Using Splitting Diagnostic"
authors:
- admin
- Weijie Su
date: ""
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: "This paper proposes a new procedure, which we term SplitSGD, for stochastic optimization with a dynamic learning rate selection rule. This procedure appropriately decreases the learning rate for better adaptation to the local geometry of the objective whenever a stationary phase is detected. The detection is performed by splitting the single thread into two and use the coherence of the two threads as a measure of stationarity. This learning rate selection is provably valid, robust, easy-to-implement, and essentially does not incur additional computational costs. Finally, we demonstrate the robustness
and satisfactory convergence performance of SplitSGD in extensive experiments. Notably, this simple procedure matches the performance of some widely used stochastic methods in their best settings.
"

# Summary. An optional shortened abstract.
# summary: 

#tags:
#- Source Themes
#featured: false

links:
url_pdf: "https://arxiv.org/pdf/1910.08597.pdf"
url_code: ""
url_dataset: ""
url_poster: ""
url_project: ""
url_slides: ""
url_source: ""
url_video: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
#image:
#  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#  focal_point: ""
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: 
---
