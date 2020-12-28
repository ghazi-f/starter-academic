---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Disentangling semantics in language throughs VAEs and a certain architectural choice"
authors: ["Ghazi Felhi", "Joseph Le Roux", "Djamé Seddah"]
date: 2020-10-22T15:48:13+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-12-24T15:48:13+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: _Arxiv_
publication_short: 

abstract: "We present an unsupervised method to obtain disentangled representations of sentences that single out semantic content. Using modified Transformers as building blocks, we train a Variational Autoencoder to translate the sentence to a fixed number of hierarchically structured latent variables. We study the influence of each latent variable in generation on the dependency structure of sentences, and on the predicate structure it yields when passed through an Open Information Extraction model. Our model could separate verbs, subjects, direct objects, and prepositional objects into latent variables we identified. We show that varying the corresponding latent variables results in varying these elements in sentences, and that swapping them between couples of sentences leads to the expected partial semantic swap."

# Summary. An optional shortened abstract.
summary: ""

tags: [	"Machine Learning (cs.LG)", "Computation and Language (cs.CL)", "Variational Autoencoders", "Disentanglement"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/pdf/2012.13031
url_code: https://github.com/ghazi-f/Disentanglement_Transformer
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
