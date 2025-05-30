---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Welcome to my site!
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: working-papers
    content:
      title: Working Papers
      filters:
        folders:
          - working-papers
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
        - name: Production Networks
          tag: Production Networks
        - name: Heterogeneity
          tag: Heterogeneity
        - name: Open Economy
          tag: Open Economy
        - name: Other
          tag: Demo
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: card
      # For Showcase view, flip alternate rows?
      flip_alt_rows: true
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
  - block: experience
    id: talks
    content:
      title: Talks
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Australasian Meeting of the Econometric Society 2023
          company: University of New South Wales
          company_url: 'https://www.esam2023.org/'
          company_logo: unsw-logo
          location: Sydney, Australia
          date_start: '2023-08-07'
          date_end: '2023-08-10'
          description: |2-
        - title: Asian Meeting of the Econometric Society 2023
          company: Nanyang Technological University
          company_url: 'https://www.ames2023ntu.org/'
          company_logo: ntu-logo
          location: Singapore
          date_start: '2023-07-28'
          date_end: '2023-07-30'
          description: |2-
        - title: North American Meeting of the Econometric Society 2023
          company: University of California, Los Angeles
          company_url: 'https://www.econometricsociety.org/regional-activities/schedule/2023/06/22/2023-North-American-Summer-Meeting-NASM-Los-Angeles-CA'
          company_logo: ucla-logo
          location: Los Angeles, California
          date_start: '2023-06-22'
          date_end: '2023-06-25'
          description: |2-
        - title: Canadian Economic Association 2023
          company: University of Manitoba
          company_url: 'https://www.economics.ca/cpages/cea2023'
          company_logo: manitoba-logo
          location: Winnipeg, Manitoba
          date_start: '2023-06-01'
          date_end: '2023-06-03'
          description: |2-
    design:
      columns: '1'
  - block: experience
    id: teaching
    content:
      title: Teaching
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: University of British Columbia
          company: Teaching Evaluations
          company_url: uploads/teaching_evaluations.pdf
          company_logo: UBC
          location: Vancouver, Canada
          date_start: '2019-08-01'
          date_end: '2023-06-30'
          description: |2-
              Teaching Assistant:
              * International Finance (Ph.D. and Masters): Spring 2023
              * International Macroeconomics and Finance (Undergrad): Spring 2023, Spring 2022
              * Monetary Theory (Undergrad 4th year): Summer 2022, Spring 2021, Spring 2020
              * International Finance (Undergrad 3rd year): Fall 2020, Summer 2021, Fall 2020, Summer 2020, Fall 2019
              * Money and Banking (Undergrad 3rd year): Summer 2023
              * Law and Economics (Undergrad 3rd year): Fall 2021
        - title: Universidad de Los Andes
          company: 
          company_url: 
          company_logo: UNIANDES
          location: Bogota, Colombia
          date_start: '2011-01-01'
          date_end: '2018-06-30'
          description: |2-
              Teaching Assistant:
              * Advanced Econometrics (Ph.D. and Masters): Spring 2018, Fall 2017, Spring 2017
              * Introduction to Macroeconomics (Undergrad 1st year): Spring 2018, Fall 2017, Spring 2017
              Undergrad Teaching Assistant:
              * Financial Derivatives (Undergrad 4th year): Spring 2016
              * Intermediate Econometrics (Undergrad 2nd year): Spring 2016, Fall 2015, Spring 2015
              * Constitutional Hermeneutics (Undergrad 2nd year): Spring 2014
              * General Criminal Law (Undergrad 3rd year): Spring 2014, Spring 2013
              * Special Criminal Law (Undergrad 3rd year): Fall 2013, Fall 2013
              * Constitutional Law (Undergrad 2rd year): Fall 2011
              * Roman Law (Undergrad 2rd year): Spring 2011
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: rojasber@hawaii.edu
      phone: +1-808-956-7071
      #appointment_url: 'https://calendly.com'
      address:
        street: 2424 Maile Way, Saunders Hall 531
        city: Honolulu
        region: Hawai'i
        postcode: '96822'
        country: United States
        country_code: US
      #directions: Office 435
      #office_hours:
      #  - 'Monday 10:00 to 13:00'
      #  - 'Wednesday 09:00 to 10:00'
      contact_links:
        - icon: twitter
          icon_pack: fab
          name: alejandro_econ
          link: 'https://twitter.com/alejandro_econ'
      # Automatically link email and phone or display as text?
      autolink: true
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #   # Enable CAPTCHA challenge to reduce spam?
      #   captcha: false
    design:
      columns: '2'
---
