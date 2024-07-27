---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About Me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  
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
          company: Mondego Lab, University of California, Irvine
          company_url: 'https://uci.edu/'
          company_logo: org-uci
          location: Irvine, CA
          date_start: '2022-09-01'
          date_end: ''
        - title: Software Engineer Internship 
          company: Corteva Agriscience
          company_url: 'https://www.corteva.com/'
          company_logo: org-corteva
          location: Johnston, IA
          date_start: '2023-06-26'
          date_end: '2023-09-15'
          # description: |2-
          #     Responsibilities include:

          #     * 
        - title: Research Assistant
          company: Laboratory for Software Design, Iowa State University
          company_url: 'https://design.cs.iastate.edu/'
          company_logo: design-lab
          location: Ames, IA
          date_start: '2021-05-01'
          date_end: '2022-05-01'
        #   description: Taught electronic engineering and researched semiconductor physics.
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: accomplishments
    id: honors&awards
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Honors & Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: 
          date_end: ''
          date_start: '2022-09-16'
          description: |2-
            * Beall Applied Innovation Proof-of-Product Grant $48,000 (2024)
            * ESEC/FSE Conference Travel Fund} $2450 (2023)
            * New Ph.D. Student Fellowship} $2500 (2022)
          organization: UCI
          organization_url: https://uci.edu/
          title: University of California, Irvine
          url: https://uci.edu/

        - certificate_url: 
          date_end: '2022-05-09'
          date_start: '2017-08-16'
          description: |2-
            * Robert and Cecile Mitchell Scholarship $2650 (2021)
            * International Incentive Scholarship $1500 (2021)
            * Global Scholars Award for Undergraduate Retention $500 (2021)
            * International Incentive Scholarship $1500 (2020)
            * Dean's List Honors (10 times)
          organization: ISU
          organization_url: https://www.iastate.edu/
          title: Iowa State University
          url: https://www.iastate.edu/
    design:
      columns: '2'
  # - block: collection
  #   id: posts
  #   content:
  #     title: Recent Posts
  #     subtitle: ''
  #     text: ''
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 5
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
  # - block: portfolio
  #   id: projects
  #   content:
  #     title: Projects
  #     filters:
  #       folders:
  #         - project
  #     # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
  #     default_button_index: 0
  #     # Filter toolbar (optional).
  #     # Add or remove as many filters (`filter_button` instances) as you like.
  #     # To show all items, set `tag` to "*".
  #     # To filter by a specific tag, set `tag` to an existing tag name.
  #     # To remove the toolbar, delete the entire `filter_button` block.
  #     buttons:
  #       - name: All
  #         tag: '*'
  #       - name: Deep Learning
  #         tag: Deep Learning
  #       - name: Other
  #         tag: Demo
  #   design:
  #     # Choose how many columns the section has. Valid values: '1' or '2'.
  #     columns: '1'
  #     view: showcase
  #     # For Showcase view, flip alternate rows?
  #     flip_alt_rows: false

  # - block: markdown
  #   content:
  #     title: Gallery
  #     subtitle: ''
  #     text: |-
  #       {{< gallery album="demo" >}}
  #   design:
  #     columns: '1'

  # - block: collection
  #   content:
  #     title: Recent Publications
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
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - event
  #   design:
  #     columns: '2'
  #     view: compact
  # - block: tag_cloud
  #   content:
  #     title: Popular Topics
  #   design:
  #     columns: '2'

# - block: features
#     content:
#       title: Skills
#       items:
#         - name: R
#           description: 90%
#           icon: r-project
#           icon_pack: fab
#         - name: Statistics
#           description: 100%
#           icon: chart-line
#           icon_pack: fas
#         - name: Photography
#           description: 10%
#           icon: camera-retro
#           icon_pack: fas
---
