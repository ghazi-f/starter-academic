---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Challenging the Semi-Supervised VAE Framework for Text Classification"
authors: ["Ghazi Felhi", "Joseph Le Roux", "Djamé Seddah"]
date: 2021-09-15T15:48:13+02:00
doi: "10.18653/v1/2021.insights-1.19"

# Schedule page publish date (NOT publication's date).
publishDate: 2022-02-10T18:20:00+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Proceedings of the Second Workshop on Insights from Negative Results in NLP
publication_short: Insights@EMNLP21

abstract: "Semi-Supervised Variational Autoencoders (SSVAEs) are widely used models for data efficient learning. In this paper, we question the adequacy of the standard design of sequence SSVAEs for the task of text classification as we exhibit two sources of overcomplexity for which we provide simplifications. These simplifications to SSVAEs preserve their theoretical soundness while providing a number of practical advantages in the semi-supervised setup where the result of training is a text classifier. These simplifications are the removal of (i) the Kullback-Liebler divergence from its objective and (ii) the fully unobserved latent variable from its probabilistic model. These changes relieve users from choosing a prior for their latent variables, make the model smaller and faster, and allow for a better flow of information into the latent variables. We compare the simplified versions to standard SSVAEs on 4 text classification tasks. On top of the above-mentioned simplification, experiments show a speed-up of 26%, while keeping equivalent classification scores. The code to reproduce our experiments is public."

# Summary. An optional shortened abstract.
summary: ""

tags: [	"Machine Learning (cs.LG)", "Computation and Language (cs.CL)", "Variational Autoencoders", "Semi-Supervised Learning"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://aclanthology.org/2021.insights-1.19/
url_code: https://github.com/ghazi-f/Challenging-SSVAEs
url_dataset:
url_poster: https://drive.google.com/file/d/1vjGTPgRjLzwXCHzzSEr3k-ZpeECG8D_p/view?usp=sharing
url_project:
url_slides:
url_source:
url_video: https://underline.io/lecture/39464-challenging-the-semi-supervised-vae-framework-for-text-classification

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
