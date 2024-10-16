---
date: "2022-10-24"
sections:

- block: about.biography
  content:
    title: Biografia
    username: admin
  id: about
- block: features
  content:
    items:
    - description: 90%
      icon: r-project
      icon_pack: fab
      name: R
    - description: 100%
      icon: chart-line
      icon_pack: fas
      name: Statistics
    - description: 10%
      icon: camera-retro
      icon_pack: fas
      name: Photography
    title: Habilidades
- block: experience
  content:
    date_format: Jan 2006
    items:
    - company: GenCoin
      company_logo: org-gc
      company_url: ""
      date_end: ""
      date_start: "2021-01-01"
      description: |2-
          Responsibilities include:

          * Analysing
          * Modelling
          * Deploying
      location: California
      title: CEO
    - company: University X
      company_logo: org-x
      company_url: ""
      date_end: "2020-12-31"
      date_start: "2016-01-01"
      description: Taught electronic engineering and researched semiconductor physics.
      location: California
      title: Professor of Semiconductor Physics
    title: Experiencia
  design:
    columns: "2"
- block: accomplishments
  content:
    date_format: Jan 2006
    items:
    - certificate_url: https://www.coursera.org
      date_end: ""
      date_start: "2021-01-25"
      description: ""
      organization: Coursera
      organization_url: https://www.coursera.org
      title: Neural Networks and Deep Learning
      url: ""
    - certificate_url: https://www.edx.org
      date_end: ""
      date_start: "2021-01-01"
      description: Formulated informed blockchain models, hypotheses, and use cases.
      organization: edX
      organization_url: https://www.edx.org
      title: Blockchain Fundamentals
      url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
    - certificate_url: https://www.datacamp.com
      date_end: "2020-12-21"
      date_start: "2020-07-01"
      description: ""
      organization: DataCamp
      organization_url: https://www.datacamp.com
      title: Object-Oriented Programming in R
      url: ""
    subtitle: null
    title: Logros
  design:
    columns: "2"
- block: collection
  content:
    count: 5
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
    title: Blog
  design:
    columns: "2"
    view: compact
  id: posts
- block: portfolio
  content:
    buttons:
    - name: All
      tag: '*'
    - name: Deep Learning
      tag: Deep Learning
    - name: Other
      tag: Demo
    default_button_index: 0
    filters:
      folders:
      - project
    title: Proyectos
  design:
    columns: "1"
    flip_alt_rows: false
    view: showcase
  id: projects
- block: markdown
  content:
    subtitle: ""
    text: '{{< gallery album="demo" >}}'
    title: Gallery
  design:
    columns: "1"
- block: collection
  content:
    filters:
      featured_only: true
      folders:
      - publication
    title: Publicaciones destacadas
  design:
    columns: "2"
    view: card
  id: featured
- block: collection
  content:
    filters:
      exclude_featured: true
      folders:
      - publication
    text: |-
      {{% callout note %}}
      Quickly discover relevant content by [filtering publications](./publication/).
      {{% /callout %}}
    title: Publicaciones cientificas recientes
  design:
    columns: "2"
    view: citation
- block: collection
  content:
    filters:
      folders:
      - event
    title: Charlas recientes y proximas
  design:
    columns: "2"
    view: compact
  id: talks
- block: tag_cloud
  content:
    title: Temas populares
  design:
    columns: "2"
- block: contact
  content:
    # address:
    #   city: Stanford
    #   country: United States
    #   country_code: US
    #   postcode: "94305"
    #   region: CA
    #   street: 450 Serra Mall
    # appointment_url: https://calendly.com
    # autolink: true
    contact_links:
    - icon: twitter
      icon_pack: fab
      link: https://twitter.com/Twitter
      name: Sigueme
    # - icon: skype
    #   icon_pack: fab
    #   link: skype:echo123?call
    #   name: Skype Me
    # - icon: video
    #   icon_pack: fas
    #   link: https://zoom.com
    #   name: Zoom Me
    # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
    email: samoy315@gmail.com
    form:
      formspree:
        id: null
      netlify:
        captcha: false
      provider: netlify
    # office_hours:
    # - Monday 10:00 to 13:00
    # - Wednesday 09:00 to 10:00
    # phone: 888 888 88 88
    subtitle: null
    text: Si desea contactarme puede enviar un mensaje por correo electronico.
    title: Contacto
  design:
    columns: "2"
  id: contact
title: null
type: landing
---
