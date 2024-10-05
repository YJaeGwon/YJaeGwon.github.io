---
# Leave the homepage title empty to use the site title
title:
date: 2024-03-25
type: landing

sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Simple Project</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Dice Game</span>
        content: <span style="font-size:90%">Game with Dice<span style="font-size:90%"></span>
        align: center
        background:
          image:
            filename: featured2.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Hugo Project</span>
        content: <span style="font-size:90%">Site with Hugo</span>
        align: center
        background:
          image:
            filename: featured3.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:90%">Ruby's Adventure</span>
        content: <span style="font-size:90%">Unity Learn Project</span>
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
