---
title: "On the Robustness to Misspecification of alpha-Posteriors and Their Variational Approximations"
# authors:
# - joint with Marco Avella Medina, José Luis Montiel Olea and Cynthia Rush
# tags:
# - Machine Learning
#author_notes:
#- "Equal contribution"
#- "Equal contribution"
date: "2022-04-01"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-04-01"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
 # publication: "*Journal of Machine Learning Research*, 23(147):1−51, 2022."
 # publication_short: "**Journal of Machine Learning Research**, 23(147):1−51, 2022."


# Summary. An optional shortened abstract.
summary: Joint with Marco Avella Medina, José Luis Montiel Olea and Cynthia Rush. *Journal of Machine Learning Research*, 23(147):1−51, 2022.

# tags:
# - Source Themes
# featured: false

# links:
# - name: ""
#   url: ""
url_pdf: "https://jmlr.org/papers/volume23/21-0386/21-0386.pdf"
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
#
---

*Journal of Machine Learning Research*, 23(147):1−51, 2022. Joint with <a href="https://sites.google.com/site/marcoavellamedina/home" target="_blank">Marco Avella Medina</span>, <span> <a href="http://www.joseluismontielolea.com/" target="_blank">José Luis Montiel Olea</a> </span>, <span> and <a href="http://www.columbia.edu/~cgr2130/" target="_blank"> Cynthia Rush</a> </span></div> 
 
Abstract:  $\alpha$-posteriors and their variational approximations distort standard posterior inference by downweighting the likelihood and introducing variational approximation errors. We show that such distortions, if tuned appropriately, reduce the Kullback-Leibler (KL) divergence from the true, but perhaps infeasible, posterior distribution when there is potential parametric model misspecification. To make this point, we derive a Bernstein-von Mises theorem showing convergence in total variation distance of $\alpha$-posteriors and their variational approximations to limiting Gaussian distributions. We use these limiting distributions to evaluate the KL divergence between true and reported posteriors. We show the KL divergence is minimized by choosing $\alpha$ strictly smaller than one, assuming there is a vanishingly small probability of model misspecification. The optimized value of $\alpha$ becomes smaller as the misspecification becomes more severe. The optimized KL divergence increases logarithmically in the magnitude of misspecification and not linearly as with the usual posterior. Moreover, the optimized variational approximations of $\alpha$-posteriors can induce additional robustness to model misspecification, beyond that obtained by optimally downweighting the likelihood.
