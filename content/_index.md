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
        url: uploads/Mutch-CV-public.pdf
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
      title: 'My Research'
      subtitle: ''
      text: |-
        I'm a music theorist working at the Max Planck Institute for Empirical Aesthetics in Frankfurt, Germany. 
        
        I study the history of musical thought, focusing on the overlooked histories of musical concepts like the cadence, the triad, and form. My work in textual criticism relies heavily on Digital Humanities approaches to analyze and represent manuscripts, and I am the digital director of the <a href="https://neubauercollegium.uchicago.edu/research/thinking-music">Thinking Music: Global Sources for the History of Music Theory</a> project.

        Music analysis is another important area of my research. I draw upon a range of analytic methodologies to study popular music from South Africa and the U.S., and I have also published form-functional and structural analyses of European art music from the eighteenth and nineteenth centuries.

    design:
      columns: '1'
  - block: collection
    content:
      title: Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      view: article-grid
      columns: 1
---
