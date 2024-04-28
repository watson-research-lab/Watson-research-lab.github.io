---
# Leave the homepage title empty to use the site title
title: Watson Research Lab
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: Welcome to the Watson Research Lab
      subtitle: by Amanda Watson
      text: 
    design:
      spacing:
        padding: [29rem, 0, 1rem, 0]
        margin: [0, 0, 0, 0]
      background:
        video:
          filename: voltera.mp4
        text_color_light: true
      
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
      view: showcase
      columns: '1'
      
  - block: collection
    content:
      title: Latest Publications
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
      page_type: publication
    design:
      view: compact
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
