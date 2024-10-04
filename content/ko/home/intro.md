---
# Use the Intro widget of the Blog template
widget: about.avatar

# This file represents a page section.
headless: true

# Order that this section will appear in.
weight: 10

author: admin
design:
  background:
    color: '#090a0b'
    text_color_light: true
#    video:
#      path:  # enter filename of a video in /assets/media
#  css_class: fullscreen
sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Simple Project</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Dice Game</span>
        content: <span style="font-size:90%">주사위를 이용한 게임<span style="font-size:90%"></span>
        align: center
        background:
          image:
            filename: featured2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Hugo Project</span>
        content: <span style="font-size:90%">Hugo를 이용한 정적 사이트</span>
        align: center
        background:
          image:
            filename: featured3.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Ruby's Adventure</span>
        content: <span style="font-size:90%">Unity Learn 프로젝트</span>
        align: center
        background:
          image:
            filename: featured4.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      slide_height: '350px'
      is_fullscreen: true
      loop: true
      interval: 3000
---

👋 안녕하세요! 저는 전북대학교 컴퓨터공학부 유재권 입니다.
    간단한 게임 토이 프로젝트를 진행합니다.
{style="font-size: 1.2rem; background: #FFB76B; background: linear-gradient(to right, #FFB76B 0%, #FFA73D 30%, #FF7C00 60%, #FF7F04 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent;"}
