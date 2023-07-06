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
        - title: Graduate Research Assistant
          company: George Mason University
          company_url: ''
          company_logo: org-gc
          location: Fairfax, VA
          date_start: '2020-08-01'
          date_end: ''
          description: |2-
              Responsibilities include:

              * Analysing
              * Modelling
              * Deploying
        - title: Researcher
          company: University of Otago
          company_url: ''
          company_logo: org-x
          location: Otago, New Zealand
          date_start: '2018-01-01'
          date_end: '2020-05-25'
          description: Taught electronic engineering and researched semiconductor physics.
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
        - name: UX
          tag: UX
        - name: Vehicles
          tag: Vehicles
        - name: Other
          tag: Other
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  # - block: collection
  #   id: featured
  #   content:
  #     title: Featured Publications
  #     filters:
  #       folders:
  #         - publication
  #       featured_only: true
  #   design:
  #     columns: '2'
  #     view: compact
  - block: collection
    content:
      title: Select Publications
      count: 3
      # text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      email: lkettle@gmu.edu
      contact_links:
        - icon: linkedin
          icon_pack: fab
          name: Connect with me!
          link: https://www.linkedin.com/in/liam-kettle/
      address:
        city: Fairfax
        region: VA
        country: United States
        country_code: US
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
