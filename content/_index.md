---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: AcademicCV-08-11-24.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        The theme of my PhD research is network time series. In particular I am interested in settings in which the data dimension is comparable to or greater than the number of observations. Tools from high dimensional statistics are required in this setting; for example: dimensionality reduction, factor models, sparse regression via penalisation, and network based approaches. 

    design:
      columns: '1'
  # - block: collection
  #   id: papers
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     view: article-grid
  #     columns: 1
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     view: article-grid
  #     columns: 1
  # - block: collection
    # id: news
    # content:
    #   title: Recent News
    #   subtitle: ''
    #   text: ''
    #   # Page type to display. E.g. post, talk, publication...
    #   page_type: post
    #   # Choose how many pages you would like to display (0 = all pages)
    #   count: 5
    #   # Filter on criteria
    #   filters:
    #     author: ""
    #     category: ""
    #     tag: ""
    #     exclude_featured: false
    #     exclude_future: false
    #     exclude_past: false
    #     publication_type: ""
    #   # Choose how many pages you would like to offset by
    #   offset: 0
    #   # Page order: descending (desc) or ascending (asc) date.
    #   order: desc
    # design:
    #   # Choose a layout view
    #   view: date-title-summary
    #   # Reduce spacing
    #   spacing:
    #     padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the Hugo Blox Builder demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-

  #       <a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/hugo-blox-builder on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!
        
  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: "bg-primary-700"
  #       css_style: ""
---
