---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        **赛博笑匠** <br>
        Cyber Comedian AI
      image:
        filename: Building-min.png
      text: |
        <br>
        
        **赛博笑匠**是一家深耕于仿生机器人、人工智能领域以及数字生命计划的科技公司，自2046年起迅速崛起，并成功成为世界领先、独一无二的科技巨头。
  
  - block: collection
    content:
      title: 公司要闻 Latest News
      subtitle:
      text:
      count: 3
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: showcase
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
        > This is a blockquote.
    design:
      columns: '1'
---
