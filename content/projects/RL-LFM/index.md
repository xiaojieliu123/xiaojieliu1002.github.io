---
title: Representation Learning in Linear Factor Models
authors: with Pepe Montiel-Olea
summary: We provide a primer on representation learning (RL) for econometricians. We use a Gaussian Linear Factor Model for an outcome variable and a vector of covariates to analyze some recent theoretical developments in the representation learning literature. 
tags:
- Machine Learning
date: "2020-07-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/amilkant
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

Abstract: Modern data sources such as videos, images, or text typically require some form of manual preprocessing prior to their use as input in statistical models. A promise of representation learning---an active area of research in machine learning---is that algorithms will, one day, learn to extract the most useful information from these data sets, thus replacing manual feature engineering. This paper uses a Gaussian Linear Factor Model for an outcome variable and a vector of covariates to analyze some recent theoretical developments in the representation learning literature. We start by deriving three sufficient representations in this model: the conditional mean of the outcome given covariates, the conditional mean of the latent factors given covariates, and the weighted least squares estimator of the latent factors. These three representations are shown to be  asymptotically invariant (in a sense we make precise) as the dimension of the covariates grows to infinity. We use a decision-theoretic approach to understand the extent to which these representations are useful for solving a downstream task. We show that the conditional mean of the outcome given covariates can be used to solve any task efficiently. This representation is also maximally insensitive---among all non-stochastic, linear, sufficient representations---to the error term in the factor model for the covariates.
