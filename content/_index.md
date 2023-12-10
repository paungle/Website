---
date: "2022-10-24"
sections:
- block: about.biography
  content:
    title: About
    username: admin
  id: about
#- block: skills
 # content:
  #  text: ""
   # title: Skills
   # username: admin
 # design:
  #  columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Research
  design:
    columns: "2"
    view: card
  id: featured
#- block: collection
#  content:
#    filters:
#     folders:
 #     - publication
  #  title: Recent Publications
 # design:
  #  columns: "2"
   # view: citation
#- block: portfolio
#  content:
#    buttons:
#    - name: All
#      tag: '*'
#    - name: ADHD
#      tag: ADHD
#    - name: Cataract Surgery
#      tag: Cataract
#    - name: Embodied Mental Models
#      tag: EMM
#    - name: Expressing Negative Emotion
#    default_button_index: 0
#    filters:
#     folders:
#      - project
#    title: Projects
#  design:
#    columns: "1"
#    flip_alt_rows: false
#    view: showcase
#  id: projects
#- block: collection
 # content:
  #  count: 5
   # filters:
    #  author: ""
     # category: ""
      # exclude_featured: false
      #exclude_future: false
      #exclude_past: false
      #folders:
      #- post
      #publication_type: ""
      #tag: ""
   # offset: 0
   # order: desc
   # subtitle: ""
   # text: ""
   # title: Recent Posts
 # design:
 #  columns: "2"
  #  view: compact
 # id: posts
- block: contact
  content:
    address:
      city: Cambridge
      country: United States
      country_code: US
      postcode: "02138"
      region: MA
      street: 33 Kirkland Street
    autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/peteraungle
      name: https://twitter.com/peteraungle
    email: peter_aungle@fas.harvard.edu
 #   form:
 #     formspree:
 #       id: null
 #     netlify:
 #       captcha: true
 #     provider: netlify
    phone: 917 518 4890
    subtitle: null
    title:
  design:
    columns: "1"
  id: contact
#- block: collection
 # content:
  #  filters:
   #   folders:
    #  - event
   # title: Recent & Upcoming Talks
 # design:
 #   columns: "2"
  #  view: compact
 # id: talks
title: ""
type: landing
---
