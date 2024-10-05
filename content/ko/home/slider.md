---
widget: slider  # Use the Slider widget as this page section
weight: 500  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: '500px'
  is_fullscreen: false
  # Automatically transition through slides?
  loop: true
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: 👋 제 블로그에 오신걸 환영합니다
      content: |
        <div class="justify-text">JaeGwon's Place</div>
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: welcome.jpg
        fit: cover
    - title: University
      content: |
        <div class="justify-text">전북대학교</div>
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: featured1.jpg
        fit: cover
    - title: toy
      content: 간단한 토이 프로젝트
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: toy.jpg
        fit: cover
    - title: Hugo project
      content: visit my github
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: featured3.jpg
        fit: cover
      link:
        icon: github
        icon_pack: fab
        text: github
        url: https://github.com/YJaeGwon/YJaeGwon.github.io
    - title: Dice game
      content: 간단한 토이 프로젝트
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: featured2.jpg
        fit: cover
      link:
        icon: github
        icon_pack: fab
        text: github
        url: https://github.com/JHuiJung/DiceHero
    - title: Development
      content: C++,JAVA
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: development.jpg
        fit: cover
---