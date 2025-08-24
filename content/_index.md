---
# Leave the homepage title empty to use the site title
title: ELDERS Research Lab
date: 2025-07-17
type: landing

sections:

  - block: hero
    content:
      title: |
        ELDERS
        Research Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        ELDERS focus on identifying the psychosocial and behavioral determinants of healthy aging, developing community-based health management models for the elderly, and conducting comparative studies on global healthy aging initiatives and management frameworks.
    
  - block: collection
    content:
        title: Research 
        # Display content from the `content/post/` folder
        filters:
          folders:
            - research
    design:
        # Choose how many columns the section has. Valid values: '1' or '2'.
        columns: '1'
        # Choose your content listing view - here we use the `showcase` view
        view: showcase
        # For the Showcase view, do you want to flip alternate rows?
        flip_alt_rows: true


  # 
  # - block: markdown
  #  content:
  #    title:
  #    subtitle: ''
  #    text:
  #  design:
  #    columns: '1'
  #    background:
  #      image: 
  #        filename: coders.jpg
  #        filters:
  #          brightness: 1
  #        parallax: false
  #        position: center
  #        size: cover
  #        text_color_light: true
  #    spacing:
  #      padding: ['20px', '0', '20px', '0']
  #    css_class: fullscreen

  - block: collection
    content:
      title: Latest Articles
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'
    
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'




---
