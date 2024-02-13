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


  - block: markdown
    content:
      title: 
      subtitle: ''
      text: |-
        ![quark-and-gluon-waves](uploads/whiteboard.jpg)
      #  {{< gallery album="activity" >}}
    design:
      columns: '1'

  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Portfolio
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 7
  #     # Filter on criteria
  #     filters:
  #       folders:
  #         - post
  #       author: ""
  #       category: ""
  #       tag: ""
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ""
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: compact
  #     columns: '2'

  - block: collection
    id: scicraft
    content:
      title: SciCraft Channel
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: scicraft
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

  - block: collection
    id: maker
    content:
      title: Technovator
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: maker
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

  - block: collection
    id: research
    content:
      title: Research
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        folders:
          - post
        author: ""
        category: ""
        tag: research
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

  # - block: accomplishments  
  #   #id: tutorial  用来做在线课程学习的成绩证明？
  #   content:
  #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
  #     title: 'Tutorial'
  #     subtitle:
  #     # Date format: https://wowchemy.com/docs/customization/#date-format
  #     date_format: Jan 2006
  #     # Accomplishments.
  #     #   Add/remove as many `item` blocks below as you like.
  #     #   `title`, `organization`, and `date_start` are the required parameters.
  #     #   Leave other parameters empty if not required.
  #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
  #     items:
  #       - certificate_url: https://www.coursera.org
  #         date_end: ''
  #         date_start: '2021-01-25'
  #         description: In Autumn 2022, I was the TA for Stanford's introductory quantum field theory class, taught by     [schoolhouse Tutor Jadon](https://schoolhouse.world/u/155443)
  #         organization: Coursera
  #         organization_url: https://www.coursera.org
  #         title: Neural Networks and Deep Learning
  #         url: ''
          
  #       - certificate_url: https://www.edx.org
  #         date_end: ''
  #         date_start: '2021-01-01'
  #         description: Formulated informed blockchain models, hypotheses, and use cases.
  #         organization: edX
  #         organization_url: https://www.edx.org
  #         title: Blockchain Fundamentals
  #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
  #       - certificate_url: https://www.datacamp.com
  #         date_end: '2020-12-21'
  #         date_start: '2020-07-01'
  #         description: ''
  #         organization: DataCamp
  #         organization_url: https://www.datacamp.com
  #         title: 'Object-Oriented Programming in R'
  #         url: ''
  #   design:
  #     columns: '2'

  - block: experience
    id: tutorial
    content:
      title: Tutorial @Schoolhouse
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: AP Physics C Mechanics All Covered (Summer Crash Course)
          company: Schoolhouse
          company_url: ''
          company_logo: schoolhouse
          location: LEARNERS 47 / 50, TOTAL SESSIONS 17
          date_start: '2023-07-22'
          date_end: '2023-10-14'
          description: |2-
              We'll go through all topics in AP Physics C Mechanics, from basic kinematics all the way to rotations and gravitation. Feel free to join even if you have no calculus background since we'll go through all math prerequisites as a part of this course (it won't turn into a calculus series). Without calculus, this course's content is very similar to AP Physics 1. Problem solving sessions where we go over specific problems after each topic will also be hosted between "lecturey" sessions. 
        - title: Calculus Group
          company: Schoolhouse
          company_url: ''
          company_logo: schoolhouse
          location: LEARNERS  4 / 10， TOTAL SESSIONS  4
          date_start: '2023-08-26'
          date_end: '2023-09-16'
          description: |2-
              This group is for Calculus students to learn math together!
              
        - title: Competitive Physics Study Group
          company: Schoolhouse
          company_url: ''
          company_logo: schoolhouse
          location: LEARNERS  9 / 12, TOTAL SESSIONS  12
          date_start: '2023-07-18'
          date_end: '2023-08-30'
          description: |2-
              The plan for now is to meet weekly and share problems we're working on. We can solve each other's confusions. Currently, there is a set of resources I found online which includes a complete set of problems that we may do over the week and discuss upon so we stay on the same track.
        - title: AP Physics 1 All Covered
          company: Schoolhouse
          company_url: ''
          company_logo: schoolhouse
          location: LEARNERS  27 / 50， TOTAL SESSIONS  15
          date_start: '2022-12-26'
          date_end: '2023-02-18'
          description: |2-
              We'll go through the basic concepts of kinematics and techniques of solving this type of problem on the AP exam. Practice problems will be covered.
              
          
    design:
      columns: '2'
      
  - block: markdown
    #id: tutorial
    content:
      title: Moderator of Physics @Schoolhouse
      subtitle: 
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      text: |2-
          Initiated “Weekly Challenge Problems” Project. These puzzles are designed to be interesting problems that are unclear at first sight. But they will be neat and fun to think about.
          ![quark-and-gluon-waves](uploads/moderator.jpg)
          - [Schoolhouse Physics Subworld Help Sheet](uploads/Moderator-of-Schoolhouse-Physics-Subworld.pdf)
      # In Autumn 2022, I was the TA for Stanford's introductory quantum field theory class, taught by [Prof. Bernhard Mistlberger](https://sites.google.com/view/bernhardmistlberger/start). We overhauled the course and produced new problem sets, which we believe strike a good balance between traditional particle physics applications, and connections to other fields. I also taught weekly sections which laid out the big picture and showed tricks for doing the problems efficiently. 
      #    - Problem sets: [1](), 
      #    - Very rough section notes: [1](),[Final exam]()
    design:
     columns: '2'


  # - block: features
  #   content:
  #     title: My Interests
  #     subtitle: Section subtitle
  #     text: Section text
  #     items:
  #       - name: R
  #         description: 90%
  #         icon: r-project
  #         icon_pack: fab
  #       - name: Statistics
  #         description: 100%
  #         icon: org-x
  #         icon_pack: custom
  #       - name: Photography
  #         description: 10%
  #         icon: 🦄
  #         icon_pack: emoji
  #         link: https://schoolhouse.world/u/155443

  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #     count: 3
  #   design:
  #     columns: '2'
  #     view: compact

  - block: collection
    id: club
    content:
      title: School Team & Club
      filters:
        folders: 
          - project
        featured_only: true
      #count: 3
    design:
      columns: '2'
      view: showcase
    #   title: Projects
    #   sgs: []
    #     # Exclude content with these tags
    #     exclude_tags: []
    #     # Which Hugo page kinds to show (https://gohugo.io/templates/section-templates/#page-kinds)
    #     kinds:
    #       - page
    #   # Field to sort by, such as Date or Title
    #   sort_by: 'Date'
    #   sort_ascending: false
    #   # Default portfolio filter button
    #   # 0 corresponds to the first button below and so on
    #   # For example, 0 will default to showing all content as the first button below shows content with *any* tag
    #   default_button_index: 0
    #   # Filter button toolbar (optional).
    #   # Add or remove as many buttons as you like.
    #   # To show all content, set `tag` to "*".
    #   # To filter by a specific tag, set `tag` to an existing tag name.
    #   # To remove the button toolbar, delete the entire `buttons` block.
    #   buttons:
    #     - name: All
    #       tag: '*'
    #     - name: Deep Learning
    #       tag: Deep Learning
    #     - name: Other
    #       tag: Dubtitle: My subtitle
    #   text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
    #   filters:
    #     # Folders to display content from
    #     folders:
    #       - project
    #     # Only show content with these tags
    #     taemo
    # design:
    #   # See Page Builder docs for all section customization options.
    #   # Choose how many columns the section has. Valid values: '1' or '2'.
    #   columns: '1'
    #   # Choose a listing view
    #   view: showcase
    #   # For Showcase view, flip alternate rows?
    #   flip_alt_rows: false

  - block: collection
    id: family
    content:
      title: Family
      filters:
        folders:
          - project
        tag: family
      #count: 3
    design:
      columns: '2'
      view: showcase

  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="club" >}}
    design:
      columns: '1'


  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # text: |-
      #   Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: jadongaoca@gmail.com
      # phone: 888 888 88 88
      # appointment_url: 'https://calendly.com'
      # address:
      #   street: 450 Serra Mall
      #   city: Stanford
      #   region: CA
      #   postcode: '94305'
      #   country: United States
      #   country_code: US
      # directions: Enter Building 1 and take the stairs to Office 200 on Floor 2
      # office_hours:
      #   - 'Monday 10:00 to 13:00'
      #   - 'Wednesday 09:00 to 10:00'
      # contact_links:
      #   - icon: twitter
      #     icon_pack: fab
      #     name: DM Me
      #     link: 'https://twitter.com/Twitter'
      #   - icon: skype
      #     icon_pack: fab
      #     name: Skype Me
      #     link: 'skype:echo123?call'
      #   - icon: video
      #     icon_pack: fas
      #     name: Zoom Me
      #     link: 'https://zoom.com'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      # form:
      #   provider: netlify
      #   formspree:
      #     id:
      #   netlify:
      #     # Enable CAPTCHA challenge to reduce spam?
      #     captcha: false
    design:
      columns: '2'
---
