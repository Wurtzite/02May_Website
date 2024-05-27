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
  - block: experience
    id: experiences 
    content:
      title: Experiences
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Viral Hepatitis Surveillance Coordinator
          company: Iowa Department of Health and Human Services Bureau of HIV, STI, and Hepatitis
          company_url: 'hhs.iowa.gov/public-health/sexually-transmitted-infections'
          company_logo:
          location: Des Moines, Iowa United States
          date_start: '2021-08-23'
          date_end: ''
          description:
        - title: Public Health Epidemiologist
          company: Sioux Lookout First Nations Health Authority
          company_url: '//www.slfnha.com/'
          company_logo:
          location: Sioux Lookout, Ontario Canada
          date_start: '2019-07-02'
          date_end: '2021-03-07'
          description:
        - title: Data Clerk
          company: Wellington Dufferin Guelph Public Health
          company_url: 
          company_logo:
          location: Guelph, Ontario Canada
          date_start: '2018-09-01'
          date_end: '2019-09-01'
          description:
        - title: Chemist, Laboratory Manager
          company: Northland Technical Laboratories
          company_url: 
          company_logo:
          location: Concord, Ontario Canada
          date_start: '2014-08-01'
          date_end: '2018-01-01'
          description: 
    design:
      columns: '2'
  - block: experience
    id: award
    content:
      # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
      title: Awards
      subtitle:
      # Date format: https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Awards & Honours.
      #   Add/remove as many `item` blocks below as you like.
      #   `title`, `organization`, and `date_start` are the required parameters.
      #   Leave other parameters empty if not required.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PS21-2103 Integrated Viral Hepatitis Surveillance and Prevention Funding for Health Departments
          Granting Agency: Centers for Disease Control and Prevention (CDC).
          date_start: '2021-05-01'
          description:|2-
           Component 1: Viral hepatitis outbreak response and surveillance
           Component 2: Viral hepatitis prevention
           Component 3: Special projects related to the infectious disease consequences of drug use
        - title: Outstanding Chapter Award
          organization: American Chemical Society
          date_start: '2014-01-01'
          date_end: '2014-05-01'
        - title: Research Grant
          organization: University of Northern Iowa
          date_start: '2013-05-01'
          date_end: '2013-08-01'
        - title: Best College LGBT Group Award
          organization: Iowa Pride Network
          date_start: '2013-01-01'
          date_end: '2013-05-01'
        - title: ACS Travel Award
          organization: American Chemical Society
          date_start: '2011-05-01'
          date_end: '2011-05-01'
        - title: SOAR Grant, Research
          organization: University of Northern Iowa
          date_start: '2011-11-01'
          date_end: '2011-11-01'
        - title: Undergraduate Research Scholarship 
          organization: University of Northern Iowa
          date_start: '2011-08-01'
          date_end: '2012-05-01'
        - title: Entrance Scholarship 
          organization: University of Northern Iowa
          date_start: '2010-08-01'
          date_end: '2014-05-01'
    design:
      columns: '2'
  - block: markdown
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      text: |-
        For research collaborations or contract analysis work please fill out the form below.
      # Contact (add or remove contact options as necessary)
      email: justinianwurtzel@gmail.com
      phone: 
      appointment_url: 'https://calendly.com/justinianmwurtzel/30min'
      address:
        street: 
        city: Des Moines
        region: IA
        postcode: '50311'
        country: United States
        country_code: US
      directions: 
      office_hours:
        - 'Monday to Friday  12:00 to 12:30 PM'
        - 'Monday to Wednesday 04:30 to 6:30 PM'
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: ''
        longitude: ''  
      contact_links:
        - icon: 
          icon_pack: 
          name: 
          link: ''
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



