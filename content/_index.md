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
      
  - block: portfolio
    id: projects
    content:
      title: Select Projects
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
        - name: UX Usabilathon
          tag: UX Usabilathon
        - name: Individual Research
          tag: Individual Research
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false

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
        - title: Doctoral Research Scholar
          company: George Mason University
          company_url: ''
          company_logo: GMU
          location: Fairfax, VA
          date_start: '2020-08-01'
          date_end: ''
          description: |2- 
              * **Enhanced driver safety awareness** through validating a vehicle communication framework involving AR and AI using surveys, A/B testing, semantic analysis, and thematic analysis of 8500+ responses.
              * **Analyzed demographic distinctions** in trust and social perceptions of autonomous vehicles and social robots through ANOVA and psychometric analysis of surveys.
              * **Increased potential for user engagement** by creating a novel rewards program for a driving application through user interviews, card sorting, competitor analysis, journey mapping, and a novel tournament-style rewards prioritization.
              * **Published strategic recommendations** to improve accessibility and UX of well-being chatbots by analyzing 19 interviews with cognitive walkthroughs and data mining of 60k+ comments from online public forums.
              * **Enabled research growth** through the management and mentoring of 20+ researchers over 7 projects through all phases of research, from study design (literature reviews and planning), data collection (in-person and online recruitment), analysis (thematic analysis, ANOVA, regression), and report writing.
        - title: Research Associate
          company: George Mason University
          company_url: ''
          company_logo: GMU
          location: Fairfax, VA
          date_start: '2023-05-25'
          date_end: '2023-08-05'
          description: |2- 
              * **Enhanced research protocol effectiveness** by advocating areas for improvement to stakeholders towards creating a novel testbed for human-machine teaming in space operations.
              * **Strengthened support for securing future grants** towards human-machine teaming through successful implementation of proof-of-concept experimental research.
              * **Collaborated with the United States Air Force Academy** and mentored 2 cadets in end-to-end research leading to their successful stakeholder presentation and conference submission.

        - title: Researcher
          company: University of Otago
          company_url: ''
          company_logo: otago-2
          location: Otago, New Zealand
          date_start: '2018-01-01'
          date_end: '2020-05-25'
          description: |2-
              * **Enhanced road safety understanding** of youth driver risk factors through the development of driving simulations coupled with SPSS regression analysis on survey data of 100+ participants.
              * **Advocated policy changes and safety initiatives** at rail level crossings through systematically identifying 40+ crash contributing factors at rail level crossings across New Zealand and Australia via thematic analysis of investigation reports and Subject Matter Expert survey.

        # - title: Psychology Teaching Assistant
        #   company: University of Otago
        #   company_url: ''
        #   company_logo: otago-2
        #   location: Otago, New Zealand
        #   date_start: '2018-01-25'
        #   date_end: '2020-05-25'
        #   description: |2-
        #       * Taught over 70 undergraduate students across 3 class laboratories, graded 100% of student assignments, and provided constructive feedback for students.
        #       * Evaluated over 50 novel system designs across various applications of Human Factors and provided recommendations for future accident analyses.
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
  
  - block: collection
    id: publications
    content:
      title: Select Publications
      subtitle: To see my full publication list, visit my [Google Scholar profile here](https://scholar.google.com/citations?user=xIH4Ww8AAAAJ&hl=en).
      # count: 3
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
