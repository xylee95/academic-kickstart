---
title: "Fast inverse design of microstructures via generative invariance networks"
authors:
# - admin
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2015-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Nature Computational Science"
publication_short: ""

abstract:The problem of the efficient design of material microstructures exhibiting desired properties spans a variety of engineering and science applications. The ability to rapidly generate microstructures that exhibit user-specified property distributions can transform the iterative process of traditional microstructure-sensitive design. We reformulate the microstructure design process using a constrained generative adversarial network (GAN) model. This approach explicitly encodes invariance constraints within GANs to generate two-phase morphologies for photovoltaic applications obeying design specifications: specifically, user-defined short-circuit current density and fill factor combinations. Such invariance constraints can be represented by differentiable, deep learning-based surrogates of full physics models mapping microstructures to photovoltaic properties. Furthermore, we propose a multi-fidelity surrogate that reduces expensive label requirements by a factor of five. Our framework enables the incorporation of expensive or non-differentiable constraints for the fast generation of microstructures (in 190 ms) with user-defined properties. Such proposed physics-aware data-driven methods for inverse design problems can be used to considerably accelerate the field of microstructure-sensitive design.

# Summary. An optional shortened abstract.
summary : The problem of the efficient design of material microstructures exhibiting desired properties spans a variety of engineering and science applications. In this paper, we proposed a computational framework and show that physics-aware deep generative model can be used for the inverse design of material microstructures. Additionally, we demonstrate that deep neural networks, efficiently trained with multi-fidelity training data doubles as ideal surrogates for evaluating the physics-based constraints within such design frameworks.

tags:
- Source Themes
featured: false

# links:
# url_pdf: ''
# url_code: ''
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
url_source: 'https://www.nature.com/articles/s43588-021-00045-8'
# url_video: ''

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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
