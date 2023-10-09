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
    id: experience
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
          company_logo: GMU
          location: Fairfax, VA
          date_start: '2020-08-01'
          date_end: ''
          description: |2- 
              * Identified 29 key insights and recommendations for effective communication between autonomous vehicles and drivers through a **systematic review** of 31 articles and analyzing 8500+ comments across 128 participants.
              * Identified actionable recommendations to increase potential for product growth of meal delivery services through **task, competitor**, and **heuristic analysis**, 5+ **user interviews**, and iterative **prototyping** to explore users' behaviors and motivations.
              * Performed **qualitative analysis** of 19 user interviews and over 1,500 comments from online public forums identifying 21 emerging themes across the parallel studies to improve accessibility, communication style, and user experiences of mental health AI chatbots.
              * **Managed 20+ researchers** over 7 projects through all phases of research, from study design (literature reviews and planing), data collection (in-person and online recrtuiment), and analysis (qualitative thematic analysis, ANOVA, moderation analysis).
              * Demonstrated technical statistics expertise using SPSS and R statistical software to analyze **quantitative** (ANOVA, multiple regression, psychometrics, Bayesian) and **qualitative** (thematic analysis) data including structured and unstructured surveys, performance metrics, and usability tests.
        - title: Summer Research Assistant
          company: George Mason University
          company_url: ''
          company_logo: GMU
          location: Fairfax, VA
          date_start: '2023-05-25'
          date_end: '2023-08-05'
          description: |2- 
              * Identified 5+ areas for improvement towards creating a testbed for human-machine teaming in space operations through conducting an experimental study with 20 participants.
              * Analyzed quantitative measures using R to provide a proof-of-concept in support of future grants towards human-machine teaming.
              * Collaborated with the United States Air Force Academy and mentored 2 cadets in end-to-end research.
        - title: Researcher
          company: University of Otago
          company_url: ''
          company_logo: otago-2
          location: Otago, New Zealand
          date_start: '2018-01-01'
          date_end: '2020-05-25'
          description: |2-
              * Developed STI-SIM driving simulations and **regressed behavioral changes** on quantitative survey data of 100+ participants using SPSS to identify distinct youth driver risk factors across visibility conditions.
              * Systematically identified 40+ crash contributing factors at rail level crossings across New Zealand and Australia through **thematic analysis** of investigation reports and **Subject Matter Expert survey**.
        - title: Psychology Teaching Assistant
          company: University of Otago
          company_url: ''
          company_logo: otago-2
          location: Otago, New Zealand
          date_start: '2018-01-25'
          date_end: '2020-05-25'
          description: |2-
              * Taught over 70 undergraduate students across 3 class laboratories, graded 100% of student assignments, and provided constructive feedback for students.
              * Evaluated over 50 novel system designs across various applications of Human Factors and provided recommendations for future accident analyses.
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
        - name: Team Projects
          tag: Team Projects
        - name: Individual Research
          tag: Individual Research
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
    id: featured
    content:
      title: Select Publications
      count: 3
      # text: |-
      filters:
        folders:
          - publication
        exclude_featured: false
        exclude_future: false
        featured_only: true
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
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
