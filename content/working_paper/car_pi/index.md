---
title: "Identification and Inference on Treatment Effects under Covariate-Adaptive Randomization and Imperfect Compliance"
# authors:
# - joint with Jose Luis Montiel Olea
# tags:
# - Machine Learning
# author_notes:
# - how to add a link?
date: "2024-04-30"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-30T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["0"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Econometrics, 217(1),161-175*"
publication_short: "**Journal of Econometrics**, 217(1),161-175"


# Summary. An optional shortened abstract.
summary: joint with Federico Bugni, Mengsi Gao, and Filip Obradovic. *New version available!*
# </a> In this paper we consider a risk-neutral firm that has an idea of unknown quality, but can perform an experiment to learn about it. The firm's goal is to decide the experiment's size and whether or not the idea should be implemented at scale after observing the experiment's outcome. We solve this problem using a Bayesian criterion (Gaussian Prior) and Minimax Regret criterion.

# tags:
# - Source Themes
# featured: false

# links:
 # - name: "http://www.joseluismontielolea.com"
#   url: ""
url_pdf: "https://arxiv.org/pdf/2406.08419"
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
Joint with <a href="https://sites.northwestern.edu/federicobugni/" target="_blank"> Federico Bugni</a> </span>, <span><a href="https://www.econ.berkeley.edu/grad/profiles/14733" target="_blank"> Mengsi Gao</a></span>, <span>and <a href="https://filipobradovic.com/" target="_blank"> Filip Obradovic</a> </span></div>

Abstract: Randomized controlled trials (RCTs) frequently utilize covariate-adaptive randomization (CAR) (e.g., stratified block randomization) and commonly suffer from imperfect compliance. This paper studies the identification and inference for the average treatment effect (ATE) and the average treatment effect on the treated (ATT) in such RCTs with a binary treatment.

We first develop characterizations of the identified sets for both estimands. Since data are generally not i.i.d.\ under CAR, these characterizations do not follow from existing results. We then provide consistent estimators of the identified sets and asymptotically valid confidence intervals for the parameters. Our asymptotic analysis leads to concrete practical recommendations regarding how to estimate the treatment assignment probabilities that enter in estimated bounds. In the case of the ATE, using sample analog assignment frequencies is more efficient than using the true assignment probabilities. On the contrary, using the true assignment probabilities is preferable for the ATT.
