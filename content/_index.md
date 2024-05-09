---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: 
    design:
      background:
        color: white
        text_color_light: false
        image:
          # Add your image background to `assets/media/`.
          filename: 
          filters:
            brightness: 1
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: 'Welcome!'
      subtitle: ''
      text: |-
        I am a computational cognitive scientist studying the learning mechanisms underlying changes in mental health. I lead a [research group](https://radulesculab.org/) at the Mt. Sinai Center for Computational Psychiatry. 
 
    design:
      columns: '1'

  - block: markdown
    content:
      title: '### News'
      subtitle: ''
      text: '- **Aug. 2024**: Attending [CCN](https://2024.ccneuro.org/) at MIT. 
             <li> **Jul. 2024**: Giving a tutorial at the SRDNA workshop at Penn. </li>
             <li> **Jul. 2024**: Giving a tutorial at the [Computational Psychiatry Conference](https://www.cpconf.org/) at UMN. </li> 
            <li> **Apr. 2024**: Gave a talk at the [Mt. Sinai Neuroscience retreat](https://friedmanbrain.icahn.mssm.edu/retreat-24/?). </li>'
    design:
      columns: '1'
  # - block: collection
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: post
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
  #     # Filter on criteria
  #     filters:
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '1'
---
