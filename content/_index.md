---
date: "2022-10-24"
sections:

#About me
- block: about.avatar
  content:
    text: null
    username: admin
  id: about

#Experience
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: Birkbeck, University of London
      company_logo: bbk
      company_url: "https://www.bbk.ac.uk/"
      date_end: ""
      date_start: "2021-03-01"
#      description: |2-
#          Responsibilities:
#          * Researching health and wellbeing
#          * Teaching organizational psychology students
#          * Supervising of research students (MSc and Doctoral)
      location: London, United Kingdom
      title: Lecturer in Psychology
      
    - company: University of Tasmania
      company_logo: utas
      company_url: "https://www.utas.edu.au/"
      date_end: ""
      date_start: "2021-04-01"
#      description:
#        Conducting research and writing up grants for the Australian Research
#        Council in partnership with Dr. Jason Satel, a member of the School of 
#        Psychological Sciences
      location: Launceston, Australia
      title: Adjunct Lecturer in Psychology

    - company: University of Tasmania
      company_logo: utas
      company_url: "https://www.utas.edu.au/"
      date_end: "2021-03-01"
      date_start: "2019-04-01"
#      description: |2-
#          Responsibilities:
#          * Researching health and wellbeing
#          * Teaching organizational psychology students
#          * Supervising research students (MSc and Doctoral)
      location: Launceston, Australia
      title: Lecturer in Psychology
    
    - company: Nottingham Trent University
      company_logo: ntu
      company_url: "https://www.ntu.ac.uk/"
      date_end: "2019-03-01"
      date_start: "2016-09-01"
#      description: |2-
#          Responsibilities:
#          * Researching on behavioral addictions and health psychology
#          * Teaching various psychology courses/modules
#          * Supervision of research students (Bsc, MSc and Doctoral)
      location: Nottingham, United Kingdom
      title: Lecturer/Senior Lecturer in Psychology

    title: (Selected) Experience
  design:
    columns: "2"
  id: experience

#Menu 'Tests'
- block: collection
  content:
    filters:
      folders:
      - event
    text: |-
      Click :point_right: **[here](./tests/)** to access the tests I have developed
      
      {{% callout note %}}
      **N.B.**: You do not need to contact me to ask for permission
      to use any of the tests and resources provided in the website
      {{% /callout %}}
      
    title: Psychometric Tests
  design:
    columns: "2"
    view: compact
  id: tests

#featured pubs
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
  id: publications

#selected pubs - excludes featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Filter **[Selected Publications](./publication/)**
      
      **N.B.**: Full list of publications available from **[ResearchGate :globe_with_meridians:](https://www.researchgate.net/profile/Halley-Pontes/research)**
      {{% /callout %}}
    title: Selected Publications
  design:
    columns: "2"
    view: cite
  id: publications

#blog posts
- block: collection
  content:
    count: 3
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
    title: Blog Posts
  design:
    columns: "2"
    view: compact
  id: posts

#tag cloud
- block: tag_cloud
  content:
    title: Topics
  design:
    columns: "2"
  id: topics

#contact me
- block: contact
  content:
    address:
      city: London
      country: United Kingdom
      country_code: GB
      postcode: "WC1E 7HX"
      # region: United Kingdom
      street: Clore Building, Malet Street, Bloomsbury
    # appointment_url: https://calendly.com FOR LATER
    autolink: true
    contact_links:
    - icon: envelope
      icon_pack: fas
      link: mailto:contactme@halleypontes.com
      name: Email
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/DrHalleyPontes
      name: Twitter
    - icon: mastodon
      icon_pack: fab
      link: https://metalhead.club/@DrHalleyPontes
      name: Mastodon
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    office_hours:
    - Mon to Fri 10:00 to 18:00
    phone: +44 (0) 203 926 1770 
    subtitle: null
#    text: You can reach me by sending a message filling out the form below or  #     contacting me through any of my social media profiles.
    title: Contact
  design:
    columns: "2"
  id: contact
  
title: null
type: landing
---
