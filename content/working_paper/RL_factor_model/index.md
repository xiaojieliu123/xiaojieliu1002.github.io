---
title: "Representation Learning in Linear Factor Models"
# authors:
# - joint with Jose Luis Montiel Olea
# tags:
# - Machine Learning
# author_notes:
# - how to add a link?
date: "2021-03-23"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Econometrics, 217(1),161-175*"
publication_short: "**Journal of Econometrics**, 217(1),161-175"


# Summary. An optional shortened abstract.
summary: joint with José Luis Montiel Olea.
# </a> In this paper we consider a risk-neutral firm that has an idea of unknown quality, but can perform an experiment to learn about it. The firm's goal is to decide the experiment's size and whether or not the idea should be implemented at scale after observing the experiment's outcome. We solve this problem using a Bayesian criterion (Gaussian Prior) and Minimax Regret criterion.

# tags:
# - Source Themes
# featured: false

# links:
 # - name: "http://www.joseluismontielolea.com"
#   url: ""
url_pdf: "https://www.amilcarvelez.com/working_paper/RL_factor_model/MV2021_submitted.pdf"
# url_pdf2: 'https://www.amilcarvelez.com/publication/KMVP_2020/KMPV_2020Appendix.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
  
Joint with <a href="http://www.joseluismontielolea.com/" target="_blank"> José Luis Montiel Olea</a> </span></div>
 
Abstract: A promise of representation learning---an active area of research in machine learning---is that algorithms will, one day, learn to extract the most useful information from modern data sources such as videos, images, or text. This paper analyzes recent theoretical developments in this literature through the lens of a Gaussian Linear Factor Model. We first derive $\emph{sufficient representations}$ for this model---defined as functions of the covariates that, upon conditioning, render the outcome variable and covariates independent. We then study the theoretical properties of these representations and establish their  \emph{asymptotic invariance}; which means the dependence of the representations on the factors' measurement error vanishes as the dimension of the covariates grows to infinity. Finally, we use a decision-theoretic approach to understand the extent to which these representations are useful for solving \emph{downstream tasks}. We show that the conditional mean of the outcome variable given covariates is an asymptotically invariant, sufficient representation, that can solve \emph{any} task efficiently, not only prediction.
