---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  #- block: skills
  #  content:
  #    title: Skills
  #    text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
  #    username: admin
  #  design:
  #    columns: '1'
  - block: experience
    id: education #                           ADDED BY ME
    content:
      title: Education
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: BSc at Moscow Institute of Physics and Technology
          company: Landau Phystech School of Physics and Research (Department of General and Applied Physics)
          company_url: 'https://landau.school/'
          company_logo: mipt-icon
          location: Moscow, Russia
          date_start: '2020-09-01'
          date_end: ''
          description: |2-
              * [Chair of Problems of Physics and Astrophysics](http://chair.lpi.ru/eng/index.html)
              * [Affiliated with Yandex chair of Data Analysis](https://mipt.ru/education/chairs/da/)
              * Advisor: [Aleksandr Beznosikov](https://anbeznosikov.github.io/index.html)
        - title: Ukrainian Physics and Mathematics Lyceum 
          company: Boarding school with the advanced study of Mathematics, Computer Science and Physics
          company_url: 'http://upml.knu.ua/'
          company_logo: upml-icon
          location: Kyiv, Ukraine
          date_start: '2016-09-01'
          date_end: '2020-08-01'
          description: |2-
              * International Olympiads prize-winner
              * National Olympiads prize-winner
              * "[All-Ukrainian mathematical fights](https://matholymp.com.ua/)" tournament contestant
              * "[Young physicists tournament](https://www.iypt.org/)" team member
              * First "[Astronomy Battles](https://www.astrosandbox.com/mainenglish)" tournament team member
    design:
      columns: '1'
  - block: experience
    id: experience # ADDED BY ME
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Department of Mathematical Fundamentals of Control, MIPT 
          company: Teaching assistant
          company_url: 'https://old.mipt.ru/education/chairs/math_basic_management/'
          company_logo: mipt-icon
          location: Moscow, Dolgoprudny, Russia
          date_start: '2023-01-01'
          date_end: ''
          description: |2-
              *  Reinforcement Learning [course](https://github.com/Andron00e/rl.mipt). Lecturer: [Yudin Nikita](https://labmmo.ru/en/team/yudin.html)
        - title: Huawei-MIPT research group
          company: Deep Learning Engineer
          company_url: ''
          company_logo: mipt-icon
          location: Moscow, Russia
          date_start: '2023-11-01'
          date_end: ''
          description: |2-
              Head: [Roland Hildebrand](https://scholar.google.fr/citations?user=uTYg6lsAAAAJ&hl=fr)
        - title: MIPT-Yandex Fundamental Research Laboratory
          company: Research student
          company_url: 'https://old.mipt.ru/science/labs/laboratory-of-fundamental-research-mipt-yandex/about/'
          company_logo: mipt-icon
          location: Moscow, Russia
          date_start: '2023-07-27'
          date_end: ''
          description: |2-
              Head: [Aleksandr Beznosikov](https://anbeznosikov.github.io/index.html)
        - title: Laboratory of Mathematical Methods of Optimization
          company: Research student
          company_url: 'https://labmmo.ru/en'
          company_logo: labmmo-icon
          location: Moscow, Dolgoprudny, Russia
          date_start: '2023-07-27'
          date_end: ''
          description: |2-
              Head: [Alexander Gasnikov](https://scholar.google.com/citations?user=AmeE8qkAAAAJ)
        - title: Laboratory of Fundamental and Applied Research of Relativistic Objects of the Universe
          company: Laboratory assistant
          company_url: 'https://rellab.mipt.ru/en/about'
          company_logo: rellab-icon
          location: Dolgoprudny, Russia
          date_start: '2022-11-12'
          date_end: '2024-04-27'
          description: |2-
              Head: DSc [Nokhrina Elena](https://www.webofscience.com/wos/author/record/C-8240-2014)
        - title: P.N. Lebedev Physical Institute
          company: Research physicist
          company_url: 'http://old.lebedev.ru/en/'
          company_logo: phian-icon
          location: Moscow, Russia
          date_start: '2022-11-12'
          date_end: '2023-07-27'
    design:
      columns: '1' #'2'
 # - block: accomplishments
 #   content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
 #     title: 'Accomplish&shy;ments'
 #     subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
 #     date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
 #     items:
 #       - certificate_url: https://www.coursera.org
 #         date_end: ''
 #         date_start: '2021-01-25'
 #         description: ''
 #         icon: coursera
 #         organization: Coursera
 #         organization_url: https://www.coursera.org
 #         title: Neural Networks and Deep Learning
 #         url: ''
 #       - certificate_url: https://www.edx.org
 #         date_end: ''
 #         date_start: '2021-01-01'
 #         description: Formulated informed blockchain models, hypotheses, and use cases.
 #         icon: edx
 #         organization: edX
 #         organization_url: https://www.edx.org
 #         title: Blockchain Fundamentals
 #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
 #       - certificate_url: https://www.datacamp.com
 #         date_end: '2020-12-21'
 #         date_start: '2020-07-01'
 #         description: ''
 #         icon: datacamp
 #         organization: DataCamp
 #         organization_url: https://www.datacamp.com
 #         title: 'Object-Oriented Programming in R'
 #         url: ''
 #   design:
 #     columns: '2'
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '1' #'2'
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
  - block: collection
    id: publications
    content:
      title: Recent Papers
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '1' #'2'
      view: list #citation
  - block: collection
    id: talks
    content:
      title: Recent Talks #Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '1' #'2'
      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
 #     default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
#  - block: contact
#    id: contact
#    content:
#      title: Contact
#      subtitle:
#      text: |-
#        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
#      email: semenov.andrei.v@gmail.com
#      phone: 888 888 88 88
#      appointment_url: 'https://calendly.com'
#      address:
#        street: 450 Serra Mall
#        city: Stanford
#        region: CA
#        postcode: '94305'
#        country: United States
#        country_code: US
#      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
#      office_hours:
#        - 'Monday 10:00 to 13:00'
#        - 'Wednesday 09:00 to 10:00'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
#      coordinates:
#        latitude: '37.4275'
#        longitude: '-122.1697'  
#      contact_links:
#        - icon: twitter
#          icon_pack: fab
#          name: DM Me
#          link: 'https://twitter.com/Twitter'
#        - icon: skype
#          icon_pack: fab
#          name: Skype Me
#          link: 'skype:echo123?call'
#        - icon: video
#          icon_pack: fas
#          name: Zoom Me
#          link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
#      autolink: true
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
          # Enable CAPTCHA challenge to reduce spam?
#          captcha: false
#    design:
#      columns: '1' #'2'
---
