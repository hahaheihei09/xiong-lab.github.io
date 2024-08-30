---
# Leave the homepage title empty to use the site title
title:
date: 2024-04-24
type: landing

sections:
  - block: hero
    content:
      title: |
        S-H
        Robotics Lab
      image:
        filename: welcome.jpg
      text: |
        <br>
        
  #      We are one of twenty-four research laboratories at the **National Engineering Research Center for Information Technology in Agriculture (Nercita)** in Beijing, China. 
        As a laboratory at the **China National Engineering Research Center for Information Technology in Agriculture (Nercita)**, we focus on advancing key technologies and their applications in strawberry harvesting robots, laser weeding robots, and robotic systems for protected tomato cultivation. By leveraging cutting-edge technologies in robotics, artificial intelligence, and horticulture, we aim to overcome technical challenges and develop fully autonomous robotic systems that are practical and beneficial for farmers.
  
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
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
