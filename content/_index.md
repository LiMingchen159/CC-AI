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
  

  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: |
        👋 欢迎关注我们**赛博笑匠**官方的媒体帐号
        👋 Free to follow us **Cyber Comedian** official media account
    design:
      background:
        # Choose colors such as from https://html-color-codes.info
        gradient_start: '#4bb4e3'
        gradient_end: '#2b94c3'
        # The gradient angle from 0-360 degrees
        gradient_angle: 180
        # Text color (true=light, false=dark, or remove for the dynamic theme color).
        text_color_light: true
---
