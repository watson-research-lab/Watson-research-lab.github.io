---
# Leave the homepage title empty to use the site title
title: Watson Research Lab
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title:
      subtitle:
      text: 
    design:
      background:
        video:
          filename: voltera.mp4
      
  - block: hero
    content:
      title: |
        Watson Research Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        The **Watson Research Lab** site is under construction. Please check back soon.
      design:
        background:
          video:
            filename: voltera.mp4
  
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
