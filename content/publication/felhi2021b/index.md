---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Towards Unsupervised Content Disentanglement in Sentence Representations via Syntactic Roles"
authors: ["Ghazi Felhi", "Joseph Le Roux", "Djamé Seddah"]
date: 2021-12-13T15:48:13+02:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2021-12-13T15:48:13+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: CtrlGen: Controllable Generative Modeling in Language and Vision
publication_short: CtrlGen

abstract: "Linking neural representations to linguistic factors is crucial in order to build and analyze NLP models interpretable by humans. Among these factors, syntactic roles (e.g. subjects, direct objects, ...) and their realizations are essential markers since they can be understood as a decomposition of predicative structures and thus the meaning of sentences. Starting from a deep probabilistic generative model with attention, we measure the interaction between latent variables and realizations of syntactic roles, and show that it is possible to obtain, without supervision, representations of sentences where different syntactic roles correspond to clearly identified different latent variables. The probabilistic model we propose is an Attention-Driven Variational Autoencoder (ADVAE). Drawing inspiration from Transformer-based machine translation models, ADVAEs enable the analysis of the interactions between latent variables and input tokens through attention. We also develop an evaluation protocol to measure disentanglement with regard to the realizations of syntactic roles. This protocol is based on attention maxima for the encoder and on disturbing individual latent variables for the decoder. Our experiments on raw English text from the SNLI dataset show that i) disentanglement of syntactic roles can be induced without supervision, ii) ADVAE separates more syntactic roles than classical sequence VAEs, iii) realizations of syntactic roles can be separately modified in sentences by mere intervention on the associated latent variables. Our work constitutes a first step towards unsupervised controllable content generation. The code for our work is publicly available."

# Summary. An optional shortened abstract.
summary: ""

tags: [	"Machine Learning (cs.LG)", "Computation and Language (cs.CL)", "Variational Autoencoders", "Disentanglement", "Unsupervised Learning]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://ctrlgenworkshop.github.io/camready/21/CameraReady/CTRLGEN%20(7).pdf
url_code: https://github.com/ghazi-f/ADVAE
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
