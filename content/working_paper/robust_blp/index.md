---
title: "On the generalization error of norm penalty linear regression models"
# authors:
# - joint with Eduardo M. Azevedo  
# - David Mao
# - Jose Luis Montiel Olea
# tags:
# - Experiments
# author_notes:
# - how to add a link?
date: "2022-11-14"
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
summary: joint with José Luis Montiel Olea, Cindy Rush, and Johannes Wiesel.
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
 
Abstract: We study linear regression problems with convex penalty functions and empirical measure of the data. Well known examples include the square-root lasso, square-root sorted L1-penalization, and  penalized least absolute deviations regression. We show that, under regularity assumptions on the penalty function, such procedures naturally provide robust generalization, as the problem can be reformulated as a distributionally robust optimization (DRO) problem for max-sliced Wasserstein ball (a type of uncertainty set of adversarial distributions), i.e. the estimate solves the penalized linear regression problem  iff it solves a best (worst-case) linear prediction problem. Our proof of this result is constructive and does not rely on duality results. We argue that the max-sliced Wasserstein ball are the natural balls to consider in this framework, as they provide a computationally efficient procedure comparable to non-robust methods and optimal robustness guarantees. In fact, our generalization bounds are of order $d/n$, up to logarithmic factors, and thus do not suffer from the curse of dimensionality as is the case for known generalization bounds when using the Wasserstein metric on $R^d$. Moreover, the bounds provide theoretical  support for recommending a regularization parameter $\delta$ of the same order for the linear regression problem.
