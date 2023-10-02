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
        - title: Research Assistant
          company: School of Computing and Information System, Singapore Management University
          company_url: 'https://scis.smu.edu.sg/'
          company_logo: ''
          location: Singapore, Singapore
          date_start: '2022-07-01'
          date_end: ''
          description: |2-
              * Supervisor: [Yuan Fang](https://www.yfang.site/)
              * Mentor: [Zemin Liu](https://zemin-liu.github.io/)
        - title: Ph.D. Student
          company: School of Computer Science and Technology, University of Science and Technology of China
          company_url: 'http://en.cs.ustc.edu.cn/main.htm'
          company_logo: ''
          location: Hefei, China
          date_start: '2019-09-01'
          date_end: ''
          description: |2-
              * Supervisor: [Xinming Zhang](http://staff.ustc.edu.cn/~xinming/)
        - title: Bachelor
          company: School of the Gifted Young, University of Science and Technology of China
          company_url: 'http://en.scgy.ustc.edu.cn/'
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
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
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
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Professional&shy;Service'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: ''
          date_end: ''
          date_start: '2023-06-27'
          description: 'Frontiers of Computer Science'
          organization: ''
          organization_url: ''
          title: Reviewer for Journals
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2023-05-23'
          description: 'NeurIPS 2023, ICLR 2024'
          organization: ''
          organization_url: ''
          title: PC Member for Conferences
          url: ''
    design:
      columns: '2'
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
