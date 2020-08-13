---
title: "Representation Learning in Linear Factor Models"
authors:
- with Pepe Montiel Olea
tags:
- Machine Learning
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2020-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
 publication: "*Work in progress*"
 publication_short: "*Draft available on requests*"

abstract:   Modern data sources such as videos, images, or text typically require some form of manual preprocessing prior to their use as input in statistical models. A promise of representation learning---an active area of research in machine learning---is that algorithms will, one day, learn to extract the most useful information from these data sets, thus replacing manual feature engineering. This paper uses a Gaussian Linear Factor Model for an outcome variable and a vector of covariates to analyze some recent theoretical developments in the representation learning literature. We start by deriving three sufficient representations in this model: the conditional mean of the outcome given covariates, the conditional mean of the latent factors given covariates, and the weighted least squares estimator of the latent factors. These three representations are shown to be  asymptotically invariant (in a sense we make precise) as the dimension of the covariates grows to infinity. We use a decision-theoretic approach to understand the extent to which these representations are useful for solving a downstream task. We show that the conditional mean of the outcome given covariates can be used to solve any task efficiently. This representation is also maximally insensitive---among all non-stochastic, linear, sufficient representations---to the error term in the factor model for the covariates.


# Summary. An optional shortened abstract.
summary: We use a Gaussian Linear Factor Model for an outcome variable and a vector of covariates to analyze some recent theoretical developments in the representation learning literature. 

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: ''
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
