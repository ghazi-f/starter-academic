---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Controlling the Interaction Between Generation and Inference in Semi-Supervised Variational Autoencoders Using Importance Weighting"
authors: ["Ghazi Felhi", "Joseph Leroux", "Djamé Seddah"]
date: 2020-10-22T15:48:13+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-10-22T15:48:13+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: _Arxiv_
publication_short: 

abstract: "Even though Variational Autoencoders (VAEs) are widely used for semi-supervised learning, the reason why they work remains unclear. In fact, the addition of the unsupervised objective is most often vaguely described as a regularization. The strength of this regularization is controlled by down-weighting the objective on the unlabeled part of the training set. Through an analysis of the objective of semi-supervised VAEs, we observe that they use the posterior of the learned generative model to guide the inference model in learning the partially observed latent variable. We show that given this observation, it is possible to gain finer control on the effect of the unsupervised objective on the training procedure. Using importance weighting, we derive two novel objectives that prioritize either one of the partially observed latent variable, or the unobserved latent variable. Experiments on the IMDB english sentiment analysis dataset and on the AG News topic classification dataset show the improvements brought by our prioritization mechanism and exhibit a behavior that is inline with our description of the inner working of Semi-Supervised VAEs."

# Summary. An optional shortened abstract.
summary: ""

tags: [	"Machine Learning (cs.LG)", "Computation and Language (cs.CL)"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2010.06549
url_code: https://github.com/ghazi-f/SSPIWO
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
