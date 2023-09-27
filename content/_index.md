---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: features
    content:
      title: Skills
      items:
        - name: English
          description: IELTS 6.5 (L7 R7 W6.5 S6)
          icon: language
          icon_pack: fas
        - name: Programme
          description: Python  Matlab  C
          icon: code
          icon_pack: fas
        - name: Software Packages
          description: Pytorch
          icon: folder
          icon_pack: fas
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
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Accomplish&shy;ments'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        # 下面一行待修改
        - certificate_url: https://drive.google.com/file/d/1DKnvtfpU3lTsos429y-JQgnUpnVrMGFM/view?usp=drive_link
          date_end: ''
          date_start: '2022-12-01'
          description: Mathematical Modeling of Real-Life Problems, Programming Analysis, and Providing a 25-Page Solution.
          organization: Consortium for Mathematics and its Applications
          organization_url: https://www.comap.com/contests/mcm-icm
          title: Honorable Mention in Interdisciplinary Contest in Modeling
          url: https://www.comap.com/contests/mcm-icm
        # 下面一行待修改
        - certificate_url: https://drive.google.com/file/d/16_uKb7o_LEIhAR3YHwO3SBlLQ-mAr891/view?usp=drive_link
          date_end: ''
          date_start: '2022-08-10'
          description:  Intelligent Tracking Camera System - Hardware implementation of deep learning neural networks.
          organization: Chinese Institute of Electronics
          organization_url: http://www.socchina.net/
          title: The 3rd prize of the National College Students' Embedded Chip and System Design Competition
          url: http://www.socchina.net/
        # 下面一行待修改
        - certificate_url: https://drive.google.com/file/d/16_uKb7o_LEIhAR3YHwO3SBlLQ-mAr891/view?usp=drive_link
          # 互联网+
          date_end: ''
          date_start: '2021-10-25'
          description: Application of Generative Adversarial Models in Image Style Transfer.
          organization: National College Student Entrepreneurship Services
          organization_url: https://cy.ncss.cn/
          title: The 3rd prize of China College Students' 'Internet+' Innovation and Entrepreneurship Competition
          url: https://cy.ncss.cn/
        # 下面一行待修改
        - certificate_url: https://drive.google.com/file/d/16_uKb7o_LEIhAR3YHwO3SBlLQ-mAr891/view?usp=drive_link
          # 国家励志
          date_end: '2022-09-01'
          date_start: '2021-09-01'
          description: Top 10% of students in the school
          organization: Ministry of Education of the People's Republic of China
          organization_url: https://drive.google.com/file/d/1QGqTFG2Xh4_D84vaR9CfBVSCBfB0WFu8/view?usp=drive_link
          title:  National Encouragement Scholarship
          url: http://www.moe.gov.cn/jyb_xwfb/xw_zt/moe_357/jyzt_2015nztzl/2015_zt06/15zt06_gxzzzc/gxzz_bzks/201508/t20150810_199203.html
        # 下面一行待修改
        - certificate_url: https://drive.google.com/file/d/16_uKb7o_LEIhAR3YHwO3SBlLQ-mAr891/view?usp=drive_link
          # 优秀学生
          date_end: '2023-09-01'
          date_start: '2021-09-01'
          description: Top 15% of students in the school
          organization: UESTC
          organization_url: https://xxgkw.uestc.edu.cn/info/1082/3777.htm
          title:  Excellent Student Scholarship
          url: https://xxgkw.uestc.edu.cn/info/1082/3777.htm
    design:
      columns: '2'
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
      columns: '2'
  - block: portfolio
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Deep Learning
          tag: Deep Learning
        - name: Mathematical Modeling
          tag: Mathematical Modeling
        - name: IoT & Embedded Systems
          tag: IoT & Embedded Systems
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
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
    content:
      title: Recent Publications
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
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: tag_cloud
    content:
      title: Popular Topics
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: test@example.org
      phone: 888 888 88 88
      appointment_url: 'https://calendly.com'
      address:
        street: 450 Serra Mall
        city: Stanford
        region: CA
        postcode: '94305'
        country: United States
        country_code: US
      directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/Twitter'
        - icon: skype
          icon_pack: fab
          name: Skype Me
          link: 'skype:echo123?call'
        - icon: video
          icon_pack: fas
          name: Zoom Me
          link: 'https://zoom.com'
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
