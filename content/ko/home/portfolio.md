---
# A section created with the Portfolio widget.
# This section displays content from `content/project/`.
# See https://docs.hugoblox.com/widget/portfolio/
widget: portfolio

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 20

title: ''
subtitle: ''

content:
  # Page type to display. E.g. project.
  page_type: project

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove the toolbar, delete the entire `filter_button` block.
  filter_button:
    - name: All
      tag: '*'
    - name: Github Site
      tag: ML
    - name: Jeonbuk National University Site
      tag: CV
    - name: Dice Game
      tag: NLP
    - name: Ruby's Adventure
      tag: Ruby

design:
  columns: '1'
  view: masonry
  flip_alt_rows: true
  background: {}
  spacing: {padding: [0, 0, 0, 0]}

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
