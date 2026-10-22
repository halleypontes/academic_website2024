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
        - statistic: "135+"
          description: |
            Publications
        - statistic: "19,000+"
          description: |
            Citations
        - statistic: "66"
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
          I am a Chartered Psychologist with the British Psychological Society (CPsychol), Member of the Australian Psychological Society
          (MAPS), and Chartered Scientist (CSci) with the Science Council. I am currently working in the School of Psychological
          Sciences at Birkbeck, University of London (United Kingdom) as a Reader in Behavioural Addiction where I teach addiction, individual differences,
          and statistics. For over ten years I have been researching emerging addictive behaviours such as gaming disorder, social media addiction, gambling disorder,
          and other online addictions.
          {style="text-align: center;"}         
          
          I received my PhD from Nottingham Trent University in the United Kingdom and have published numerous peer-reviewed studies in several scientific 
          journals (see my **[ResearchGate](https://www.researchgate.net/profile/Halley-Pontes)** profile for a full list).
          {style="text-align: center;"}
          
          Recently, I was featured in the **[2026 Stanford-Elsevier World's Top 2% Scientists List](https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/9)**.
          I was also awarded the Durand Jacobs Award from McGill University (Canada) and the Early Career Research Award from the Australian Psychological 
          Society (Australia) for my contributions to the psychology of addictive behaviours and cyberpsychology.
          {style="text-align: center;"}
  
          My email **[PGP Public Key](https://drive.proton.me/urls/GYZNM1652C#C34xqQi4LYoU)** fingerprint is: DE26 2BED FB0D C0ED 97F7 
          DD95 234E 9809 AEDA EAC8.
          {style="text-align: center;"}
          
    design:
      columns: '1'
  - block: collection
    content:
      title: Latest post
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 1
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
      view: list
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---
