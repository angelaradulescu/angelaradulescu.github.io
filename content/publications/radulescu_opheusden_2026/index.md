---
title: 'A resource-rational account of human eye movements during immersive visual search'

authors:
- admin
- Bas van Opheusden
- Frederick Callaway
- Thomas L. Griffiths
- James M. Hillis
date: "2026-02-01T00:00:00Z"
doi: "10.1162/OPMI.a.322"

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-02-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: "In *Open Mind*"
publication_short: "In *Open Mind*"

abstract: The nature of eye movements during visual search has been widely studied in psychology and neuroscience. Virtual reality (VR) paradigms provide an opportunity to test whether computational models of search can predict naturalistic search behavior. However, existing ideal observer models are constrained by strong assumptions about the structure of the world, rendering them impractical for modeling the complexity of environments that can be studied in VR. To address these limitations, we frame naturalistic visual search as a problem of allocating limited cognitive resources, formalized as a meta-level Markov decision process (meta-MDP) over a representation of the environment encoded by a deep neural network. We train reinforcement learning agents to solve the meta-MDP, showing that the agents’ optimal policy converges to a classic ideal observer model of search developed for simplified environments. We compare the learned policy with human gaze data from a visual search experiment conducted in VR, finding a qualitative and quantitative correspondence between model predictions and human behavior. Our results suggest that gaze behavior in naturalistic visual search is consistent with rational allocation of limited cognitive resources.

# Summary. An optional shortened abstract.
summary: ''

# tags:
# - Source Themes
# featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://direct.mit.edu/opmi/article/doi/10.1162/OPMI.a.322/135355/A-Resource-Rational-Account-of-Human-Eye-Movements'
url_code: 'https://github.com/angelaradulescu/modeling-eye-movements-vr'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

When you search for something in a rich 3D scene, your eyes follow specific patterns that reveal how the mind knows what to pay attention to. Virtual reality (VR) lets us measure that behavior in settings closer to everyday life. Standard models often assume an unrealistically simple world, so in this paper we ask how someone with limited time and attention ought to move their gaze when the search environment is complex and respects the structure of the real world. A computational model trained with reinforcement learning predicts gaze shifts that match people’s data in VR, suggesting that naturalistic visual search may reflect a rational use of limited mental resources.
