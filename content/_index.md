---
# Leave the homepage title empty to use the site title
title:
date: 2024-10-06
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: background-3.webp
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "120+"
          description: |
            Publications
        - statistic: "15,280+"
          description: |
            Citations
        - statistic: "61"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
#      title: 'Welcome'
      subtitle: ''
      text: |-
          I am a Chartered Psychologist of the British Psychological Society (CPsychol), Member of the Australian Psychological Society
          (MAPS), and Chartered Scientist (CSci) of the Science Council. I am currently working in the School of Psychological
          Sciences at Birkbeck, University of London (United Kingdom) as a Senior Lecturer where I teach statistics, addiction,
          and individual differences. For over ten years I have been researching emerging addictive behaviours such as gaming
          disorder, social media addiction, gambling disorder, and other online addictions.
          I received my PhD from Nottingham Trent University in the United Kingdom and have published numerous studies (see my 
          **[ResearchGate](https://www.researchgate.net/profile/Halley-Pontes)** profile for a full list) in several scientific 
          journals and presented my research work at numerous international conferences. My research has been previously awarded with the 
          Durand Jacobs Award from McGill University (Canada) and the Early Career Research Award from the Australian Psychological 
          Society (Australia) for its contributions to the psychology of addictive behaviors and cyberpsychology.
          {style="text-align: center;"}
          
          My email **[PGP Public Key](https://drive.proton.me/urls/GYZNM1652C#C34xqQi4LYoU)** fingerprint is: DE26 2BED FB0D C0ED 97F7 
          DD95 234E 9809 AEDA EAC8.
          {style="text-align: center;"}
          
    design:
      columns: '1'
  - block: collection
    content:
      title: Latest posts
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
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
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
