---
title: "Modeling human eye movements during immersive visual search"
authors:
- admin
- Bas van Opheusden
- Frederick Callaway
- Thomas L. Griffiths
- James M. Hillis
date: "2022-12-01T00:00:00Z"
doi: ""

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

# Schedule page publish date (NOT publication's date).
publishDate: "2022-12-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: The nature of eye movements during visual search has been widely studied in psychology and neuroscience. Virtual reality (VR) paradigms provide an opportunity to test whether computational models of search can predict naturalistic search behavior. However, existing ideal observer models are constrained by strong assumptions about the structure of the world, rendering them impractical for modeling the complexity of environments that can be studied in VR. To address these limitations, we frame naturalistic visual search as a problem of allocating limited cognitive resources, formalized as a meta-level Markov decision process (meta-MDP) over a representation of the environment encoded by a deep neural network. We train reinforcement learning agents to solve the meta-MDP, showing that the agents’ optimal policy converges to a classic ideal observer model of search developed for simplified environments. We compare the learned policy with human gaze data from a visual search experiment conducted in VR, finding a qualitative and quantitative correspondence between model predictions and human behavior. Our results suggest that gaze behavior in naturalistic visual search is consistent with rational allocation of limited cognitive resources.

# Summary. An optional shortened abstract.
summary: ''

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://www.biorxiv.org/content/10.1101/2022.12.01.518717v1
url_code: ''
url_dataset: ''
url_poster: 'https://baicsworkshop.github.io/program/baics_33.html'
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
slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
