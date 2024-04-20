---
# Leave the homepage title empty to use the site title
title: Watson Research Lab
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
    design:
      background:
        color: '#090a0b'
        text_color_light: true
        video:
          path: voltera.mp4
      css_class: d-flex fullscreen align-items-center
  - block: markdown
    content:
      title:
      subtitle: ''
      text: 
    design:
      columns: '1'
      background:
        video:
          path : voltera.mp4
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
      
  - block: hero
    content:
      title: |
        Watson Research Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Watson Research Lab** site is under construction. Please check back soon.
  
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
