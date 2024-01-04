---
# Leave the homepage title empty to use the site title
title: Michael Ryan
date: 2022-12-1
type: landing

sections:
  - block: v1/about
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:
  - block: collection
    id: featured
    content:
      title: Selected Research
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    id: research
    content:
      title: Research
      filters:
        folders:
          - publication
        featured_only: false
    design:
      columns: '2'
      view: list
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      columns: '2'
      view: compact
  - block: experience
    id: experience
    content:
      title: Work Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Software Engineer Intern
          company: Microsoft Corporation
          company_url: 'https://www.microsoft.com/en-us/'
          company_logo: msft.svg
          location: Seattle, WA
          date_start: '2022-05-16'
          date_end: '2022-08-09'
          description: |2-
              * Designed and programmed static analysis tool in C++ for identifying security vulnerabilities throughout Windows OS.
        - title: Software Engineer Intern
          company: Microsoft Corporation
          company_url: 'https://www.microsoft.com/en-us/'
          company_logo: msft.svg
          location: Virtual
          date_start: '2021-05-16'
          date_end: '2021-08-09'
          description: |2-
              * Refactored existing codebase from .NET Framework to .NET Core.
              * Ported server-specific architecture to serverless functional units using Azure Durable Functions.

        - title: Software Engineer Intern
          company: Uber Inc.
          company_url: 'https://www.uber.com'
          company_logo: uber.svg
          location: Virtual
          date_start: '2020-05-16'
          date_end: '2020-08-09'
          description: |2-
              * Implemented end-to-end testing in GoLang for bike, scooter, and moped rentals by building a simulated 3rd party CRUD API.
    design:
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
        - name: Natural Language Processing
          tag: Natural Language Processing
        - name: Computer Vision
          tag: Computer Vision
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: showcase
      # For Showcase view, flip alternate rows?
      flip_alt_rows: false
  - block: accomplishments
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: 'Awards'
      subtitle:
      # Date format: https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Accomplishments.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - certificate_url: https://honorsprogram.gatech.edu/honors-program-pathways/research
          date_end: ''
          date_start: '2022-12-19'
          description: 'Awarded for completing Honors Level Coursework and Approved Research as an undergraduate at Georgia Tech'
          organization: 'Georgia Tech Honors Program'
          organization_url: https://honorsprogram.gatech.edu
          title: Honors Program Distinction in Research
          url: ''
        - certificate_url: ''
          date_end: ''
          date_start: '2022-03-01'
          description: 'Awarded for contributions to teaching excellence at Georgia Tech School of Interactive Computing'
          organization: 'Georgia Tech Center for Teaching and Learning'
          organization_url: https://ctl.gatech.edu/home
          title: Outstanding Undergraduate TA for Interactive Computing
          url: ''
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: 
      # Contact (add or remove contact options as necessary)
      email: michaeljryan@stanford.edu
      # address:
      #   street: 756 W Peachtree St NW
      #   city: Atlanta
      #   region: GA
      #   postcode: '30308'
      #   country: United States
      #   country_code: US
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: DM Me
          link: 'https://twitter.com/michaelryan207'
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
