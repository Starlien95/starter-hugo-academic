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
    id: education
    content:
      title: Education
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Student
          company: School of Computer Science and Technology, University of Science and Technology of China
          company_url: 'http://en.cs.ustc.edu.cn/main.htm'
          company_logo: ''
          location: Hefei, China
          date_start: '2019-09-01'
          date_end: ''
          description: |2-
              * Supervisor: [Xinming Zhang]
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
  - block: experience
    id: experience
    content:
      title: Experiences
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
          description: |2-
              * Supervisor: [Yuan Fang](https://www.yfang.site/)
              * Mentor: [Zemin Liu](https://zemin-liu.github.io/)
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Featured Papers
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: other
    content:
      title: Other Papers
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: experience
    id: services
    content:
      title: Academic Service
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Program Committee Member
          company: ''
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2023-05-11'
          date_end: ''
          description: |2-
              * NeurIPS (2023)
              * ICLR (2024)
              * ICML (2024)
              * WWW (2024)
              * CVPR (2024)
              * ICMR (2024)
        - title: Journal Reviewer
          company: ''
          company_url: ''
          company_logo: ''
          location: ''
          date_start: '2023-05-11'
          date_end: ''
          description: |2-
              * Frontiers of Computer Science
              * PeerJ Computer Science
    design:
      columns: '2'
---
