---
# Display name
title: 유재권

# Is this the primary user of the site?
superuser: true

# Role/position
role: 'Computer Engineering'

# Status emoji
status:
  icon: ⌨️

# Organizations/Affiliations
#organizations:
#- name: 腾讯
#  url: ""

# Short bio (displayed in user profile at end of posts)
bio: 전북대학교 컴퓨터공학부에 재학중입니다.

#interests:
#- Artificial Intelligence
#- Computational Linguistics
#- Information Retrieval

#education:
#  courses:
#  - course: PhD in Artificial Intelligence
#    institution: Stanford University
#    year: 2012
#  - course: MEng in Artificial Intelligence
#    institution: Massachusetts Institute of Technology
#    year: 2009
#  - course: BSc in Artificial Intelligence
#    institution: Massachusetts Institute of Technology
#    year: 2008

# Social/Academic Networking
# For available icons, see: https://docs.hugoblox.com/getting-started/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "#contact" for contact widget.
social:
  - icon: envelope
    icon_pack: fas
    link: mailto:202011690@jbnu.ac.kr
  - icon: github
    icon_pack: fab
    link: https://github.com/YJaeGwon/YJaeGwon.github.io
  - icon: cv
    icon_pack: ai
    link: files/instruction.pdf
# Uncomment below for Github link
#- icon: github
#  icon_pack: fab
#  link: https://github.com/gcushen

# Link to a PDF of your resume/CV from the About widget.
# To enable, copy your resume/CV to `static/files/cv.pdf` and uncomment the lines below.
  

# Enter email to display Gravatar (if Gravatar enabled in Config)
#email: ""
sections:

  - block: features
    content:
      title: 
      text: <br><span style="font-size:125%">Simple Project</span>

  - block: slider
    content:
      slides:

      - title: <span style="font-size:90%">Dice Game</span>
        content: <span style="font-size:90%">주사위를 이용한 게임<span style="font-size:90%">
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
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---

