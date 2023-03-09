---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Visiting Research Student
          company: School of Computing and Information System, Singapore Management University
          company_url: 'https://scis.smu.edu.sg/'
          company_logo: ''
          location: Singapore, Singapore
          date_start: '2022-07-01'
          date_end: ''
          description: 'Supervisor: Yuan Fang'
        - title: Ph.D. Student
          company: School of Computer Science and Technology, University of Science and Technology of China
          company_url: 'http://cs.ustc.edu.cn/main.htm'
          company_logo: ''
          location: Hefei, China
          date_start: '2019-09-01'
          date_end: ''
          description: 
            Supervisor: 
            * Xinming Zhang
        - title: Bachelor
          company: School of the Gifted Young, University of Science and Technology of China
          company_url: 'https://sgy.ustc.edu.cn/'
          company_logo: ''
          location: Hefei, China
          date_start: '2015-09-01'
          date_end: '2019-07-01'
          description: ''
    design:
      columns: '2'
  - block: collection
    id: featured
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
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
      # Contact (add or remove contact options as necessary)
      email: yxt95@mail.ustc.edu.cn
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '2'
---
