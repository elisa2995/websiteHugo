---
# Leave the homepage title empty to use the site title
title: Elisa Chiapponi
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text: I am a PhD student in Web, Network and Application Security enrolled at the Sorbonne Université. I work on my research project at EURECOM and Amadeus IT Group, under the supervision of prof.Marc Dacier. My research focuses on the analysis and mitigation of the new generation of botnets, in particular the ones performing web scraping. My goal is to find practical means to defeat them. The starting point of my project is understanding the ecosystem of scraping bots. This consists of identifying the actors behind this business and their motivations, understanding the various techniques they exploit and the infrastructures they take advantage of. I am currently studying Residential IP Proxies. Scrapers exploit these services to have a vast network of residential IP addresses which help bypass current countermeasure tecniques.
  - block: experience
    id: work
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: CEO
          company: GenCoin
          company_url: ''
          company_logo: org-gc
          location: California
          date_start: '2021-01-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Professor of Semiconductor Physics
          company: University X
          company_url: ''
          company_logo: org-x
          location: California
          date_start: '2016-01-01'
          date_end: '2020-12-31'
          description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: collection
    id: pubblications
    content:    
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact

  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: elisa.chiapponi@eurecom.fr
      phone: +33 (0)4 93 00 82 75
      address:
        street: 450 Route des Chappes
        city: Biot
        region: 
        postcode: '06410'
        country: United States
        country_code: France
      directions: Office 369 (Floor -3)
      # Automatically link email and phone or display as text?
      autolink: true
---
