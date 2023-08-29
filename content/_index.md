---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing
sections:
  - block: about.biography
    id: about
    content:
      title: About me
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: addons
    content:
      title: Addons
      filters:
        folders:
          - addons
      text: |
        ***Conferences***
    
        PhD Symposium. And the winner is: https://www.ubtaktuell.uni-bayreuth.de/phd-symposium-2023 (Organized & Attended)

        PhD Symposium of the CRC 1375 (2022). Three days of exciting talks and good atmosphere. Read about it here: https://ubtaktuell.uni-bayreuth.de/sfb1357-doctoral-seminar (Organized & Attended)

        ***Workshops***
        
        Prepare for doctoral defence held by Dr. Dunja Mohr (Organized & Attended)
        
        The patriarchy of things - and how it influences my research held by Dr. Elena Köster (Attended)

        WiN Kick-Off Career Orientation Workshop held by Dr. Alina Jahn (Organized & Attended)

        Write-it-Right Workshop held by Gadi Rothenberg and Christopher Lowe (Attended)

        ***Additional acitivities***

        PhD Representative of the CRC 1375 (2021-2023)

        ***Supervision***

        Bachelorthesis - Max Stocker (2021): Influence of water surface and bubble bursting on near-surface turbulence in a wind tunnel

    design:
      columns: '2'
      view: compact
  - block: collection
    id: talks
    content:
      title: Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: eike.esders0uni-bayreuth.de
      address:
        street: Universitätsstrasse 30
        city: Bayreuth
        postcode: '95440'
        country: Germany
        country_code: DE
      # Automatically link email and phone or display as text?
      autolink: false
    design:
      columns: '2'
---
