---
date: "2022-10-24"
sections:

- block: about.biography
  id: about
  content:
    title: 
    # Choose a user profile to display (a folder name within `content/authors/`)
    username: admin    

#- block: experience
#  content:
#    date_format: Jan 2006
#    items:
#    - company: Arizona State University
#      company_logo: 
#      company_url: ""
#      date_end: ""
#      date_start: "2020-08-01"
#      description: 
#      location: Tempe/AZ
#      title: Graduate Research And Teaching Assistant
#    - company: Ikem Isik Auditory Rehabilitation Center
#      company_logo: 
#      company_url: ""
#      date_end: "2019-06-30"
#      date_start: "2017-09-01"
#      description: 
#      location: Istanbul/Turkey
#      title: Audiologist
#    - company: Universita degli Studi di Padova
#      company_logo: 
#      company_url: ""
#      date_end: "2015-05-01"
#      date_start: "2015-09-01"
#      description: 
#      location: Padova/Italy
#      title: Intern Audiologist
#    title: Background
#  design:
#    columns: "2"
- block: collection
  content:
    count: 1
    filters:
      author: ""
      category: ""
      exclude_featured: false
      exclude_future: false
      exclude_past: false
      folders:
      - post
      publication_type: ""
      tag: ""
    offset: 0
    order: desc
    subtitle: ""
    text: ""
    title: Recent Posts
  design:
    columns: "2"
    view: compact
  id: posts    
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Featured Publications
  design:
    columns: "2"
    view: card
  id: featured

#- block: collection
#  content:
#    filters:
#      exclude_featured: true
#      folders:
#      - publication
#    text: |-
#      {{% callout note %}}
#      Quickly discover relevant content by [filtering publications](./publication/).
#      {{% /callout %}}
#    title: Recent Publications
#  design:
#    columns: "2"
#    view: citation

- block: contact
  content:
    contact_links:
    email: narslan@asu.edu
#    form:
#      provider: netlify    
#      netlify:
#        captcha: true
#    subtitle: null
    text: Please feel free to contact me via email if you have any questions or inquiries.
    title: Contact
#    extra:
#      - raw_html: |
#         <a class="twitter-timeline" data-width="400" data-height="400" href="https://twitter.com/niyazioarslan?ref_src=twsrc%5Etfw">Tweets by niyazioarslan</a> 
#          <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>
  design:
    columns: "2"
  id: contact
title: null
type: landing
extra:

---

