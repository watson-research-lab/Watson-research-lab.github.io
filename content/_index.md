---
# Leave the homepage title empty to use the site title
title:
date: 2023-1-12
type: landing
sections:
  - block: about.avatar
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: |-
        👋 Welcome to vampir.io website.
        {style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
    design:
      background:
        color: '#090a0b'
        text_color_light: true
        video:
          path: background-video.mp4
        #color: black
        #text_color_light: true
        #image:
        # Add your image background to `assets/media/`.
        #  filename: space.jpg
        #  filters:
        #    brightness: 0.2
        #    size: cover
        #    position: center
        #    parallax: false
        #video: 
        #{{< youtube w7Ft2ymGmfc >}}
        #  # Name of video in `assets/media/`.
        #  background.video.filename: background-video.mp4
        #  filename: background-video.mp4
        #filename: 
        #{{< youtube w7Ft2ymGmfc >}}
        #  filename: {{< video src="background-video.mp4" controls="no" >}}
        #  # Post-processing: flip the video horizontally?
        #  flip: false
      css_class: d-flex fullscreen align-items-center
---
