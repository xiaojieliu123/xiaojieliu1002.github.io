---
title: "The out-of-sample prediction error of the square-root-LASSO and related estimators"
# authors:
# - joint with Eduardo M. Azevedo  
# - David Mao
# - Jose Luis Montiel Olea
# tags:
# - Experiments
# author_notes:
# - how to add a link?
date: "2024-04-10"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-04-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Econometrics, 217(1),161-175*"
publication_short: "**Journal of Econometrics**, 217(1),161-175"


# Summary. An optional shortened abstract.
summary: joint with José Luis Montiel Olea, Cynthia Rush, and Johannes Wiesel. *New version available!*
# </a> In this paper we consider a risk-neutral firm that has an idea of unknown quality, but can perform an experiment to learn about it. The firm's goal is to decide the experiment's size and whether or not the idea should be implemented at scale after observing the experiment's outcome. We solve this problem using a Bayesian criterion (Gaussian Prior) and Minimax Regret criterion.

# tags:
# - Source Themes
# featured: false

# links:
 # - name: "http://www.joseluismontielolea.com"
#   url: ""
url_pdf: "https://arxiv.org/pdf/2211.07608.pdf"
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
  
Joint with <a href="http://www.joseluismontielolea.com/" target="_blank"> José Luis Montiel Olea</a> </span>, <span><a href="http://www.columbia.edu/~cgr2130/" target="_blank"> Cynthia Rush</a></span>, <span>and <a href="https://sites.google.com/view/johannes-wiesel?pli=1" target="_blank"> Johannes Wiesel</a> </span></div>
 
Abstract: We study the classical problem of predicting an outcome variable, $Y$, using a linear combination of a $d$-dimensional covariate vector, $\mathbf{X}$. We are interested in linear predictors whose coefficients solve:
\begin{align*}
\inf_{\boldsymbol{\beta} \in \mathbb{R}^d} \left( \mathbb{E}_{\mathbb{P}_n} \left[ \left|Y-\mathbf{X}^{\top}\beta \right|^r \right] \right)^{1/r} +\delta \, \rho\left(\boldsymbol{\beta}\right),
\end{align*}
where $\delta>0$ is a regularization parameter, $\rho:\mathbb{R}^d\to \mathbb{R}_+$ is a convex penalty function, $\mathbb{P}_n$ is the empirical distribution of the data, and $r\geq 1$. Our main contribution is a new bound on the out-of-sample prediction error of
such estimators. 

The new bound is obtained by combining three new sets of results. First, we provide conditions under which linear predictors based on these estimators solve a *distributionally robust optimization* problem: they minimize the worst-case prediction error over distributions that are close to each other in a type of *max-sliced Wasserstein metric*. Second, we provide a detailed finite-sample and asymptotic analysis of the statistical properties of the balls of distributions over which the worst-case prediction error is analyzed. Third, we present an oracle recommendation for the choice of regularization parameter, $\delta$, that guarantees good out-of-sample prediction error.  
