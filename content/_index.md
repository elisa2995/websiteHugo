---
# Leave the homepage title empty to use the site title
title: Elisa Chiapponi // WEBSITE UNDER CONSTRUCTION, for the time being please refer to https://elisa2995.github.io/
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
        - title: PhD researcher
          company: EURECOM - Amadeus
          company_url: 'https://amadeus.com/en'
          company_url: 'https://www.eurecom.fr/en'
          company_logo: 
          location: Biot, France
          date_start: '2020-04-01'
          date_end: ''
          description: |2-
              .
              
        - title: Visiting PhD student
          company: KAUST - Resilient Computing and Cybersecurity Center (RC3)
          company_url: 'https://cemse.kaust.edu.sa/rc3'
          company_logo: 
          location: Thuwal, Saudi Arabia
          date_start: '2022-02-01'
          date_end: '2022-03-01'
          description: |2-
              During this visiting experience, I had the opportunity to interact with the members of RC3 (Resilient Computing and Cybersecurity Center) and work in close collaboration with them about Residentail IP Proxy providers.
              
        - title: OMAC COVID-19 Hackaton Top 30 Team Member
          company: Dubai Future Fundation
          company_url: 'https://www.dubaifuture.ae/'
          company_logo: 
          location: Virtual
          date_start: '2020-04-01'
          date_end: '2020-05-31'
          description: OMAC (One Million Arab Coders) Covid-19 Hackaton was launched to find solutions to problems that emerged in the first stages of the pandemic. Our team, composed of 6 people from different domains decided to submit the project of an application that would help people wanting to do volunteering to find the volunteering association that best suits them. Our idea was selected with other 29 among the 1200 proposed ones. We had 5 days to build a prototype of the application and business plan for it. We were helped and guided by mentors of the hackaton.

        - title: Application SOC research intern
          company: Amadeus
          company_url: 'https://amadeus.com/en'
          company_logo: 
          location: Biot, France
          date_start: '2019-07-01'
          date_end: '2020-01-31'
          description: My interniship was about the creation and development of a honeypot able to mitigate attacks of scraping bots towards the company booking domains. This work was the topic of my Master of Science thesis.
          
        - title: Bachelor thesist
          company: BMI Mario Stefanelli - Universitá degli studi di Pavia
          company_url: 'http://www.labmedinfo.org/en/10-2/'
          company_logo: 
          location: Pavia, Italy
          date_start: '2017-02-01'
          date_end: '2017-07-31'
          description: I participated in the project and development of the first version of a web app to monitor the ketogenic diet. The application is currently used by the Health and Nutrition center of the university.
          
        - title: Front-desk librarian
          company: Universitá degli studi di Pavia
          company_url: 'https://web-en.unipv.it/'
          company_logo: 
          location: Pavia, Italy
          date_start: '2017-01-01'
          date_end: '2017-06-30'
          description: I took part in a part-time collaboration with the university to work in the library.
         
        - title: Summer intern
          company: Chemistry Department, Universitá degli studi di Pavia
          company_url: 'https://scichim.unipv.it/'
          company_logo: 
          location: Pavia, Italy
          date_start: '2013-06-01'
          date_end: '2013-06-30'
          description: I took part in the summer internship program for high school students organized by the Chemistry and Physics division of the university. I was assigned at the Phisical Chemistry department and I studied isomorphic cristals.
         

    design:
      columns: '2'
  # - block: collection
  #   id: pubblications
  #   content:    
  #     title: Publications
  #     text: |-
  #       {{% callout note %}}
  #       Quickly discover relevant content by [filtering publications](./publication/).
  #       {{% /callout %}}
  #     filters:
  #       folders:
  #         - publication
  #       exclude_featured: true
  #   design:
  #     columns: '2'
  #     view: citation
  # - block: collection
  #   id: talks
  #   content:
  #     title: Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact

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
