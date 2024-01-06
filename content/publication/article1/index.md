---
title: "Machine-learning surrogate model for accelerating the search of stable ternary alloys"
authors:
- Michael Minotakis
- Hugo Rossignol
- Matteo Cobelli
- Stefano Sanvito
author_notes:
- "Equal contribution"
- "Equal contribution"
date: ""
doi: "https://doi.org/10.1103/PhysRevMaterials.7.093802"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-22T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Physical Review Materials (7)*"
publication_short: ""

abstract: 'The prediction of phase diagrams in the search for new phases is a complex and computationally intensive task. Density functional theory provides, in many situations, the desired accuracy, but its throughput becomes prohibitively limited as the number of species involved grows, even when used with local and semilocal functionals. Here, we explore the possibility of integrating machine-learning models in the workflow for the construction of ternary convex hull diagrams. In particular, we train a set of spectral neighbor-analysis potentials (SNAPs) over readily available binary phases, and we establish whether this is good enough to predict the energies of novel ternaries. Such a strategy does not require any new calculations specific for the construction of the model, but just avails of data stored in binary-phase-diagram repositories. We find that a so-constructed SNAP is capable of accurate total-energy estimates for ternary phases close to the equilibrium geometry but, in general, is not able to perform atomic relaxation. This is because during a typical relaxation path, a given phase traverses regions in the parameter space poorly represented by the training set. Different metrics are then investigated to assess how well an unknown structure is described by a given SNAP model, and we find that the standard deviation of an ensemble of SNAPs provides a fast and non-specie-specific metric. Overall, we show that it is possible to train machine-learning interatomic potentials on readily available binary-compound data to effectively screen ternary compounds in a high-throughput search.'

# Summary. An optional shortened abstract.
summary: ''

tags:
- Interatomic & molecular potentials
- Density Functional Theory
- Machine Learning
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://journals.aps.org/prmaterials/abstract/10.1103/PhysRevMaterials.7.093802'
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
  preview_only: True

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

---

