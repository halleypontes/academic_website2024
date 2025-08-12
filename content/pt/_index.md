---
# Leave the homepage title empty to use the site title
title:
date: 2024-09-14
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
        - statistic: "124+"
          description: |
            Publicações
        - statistic: "15,700+"
          description: |
            Citações
        - statistic: "62"
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
          {{% callout warning %}}
          **A tradução do site para o Português ainda está a ser finalizada**
          {{% /callout %}}

          Sou psicólogo filiado à British Psychological Society (CPsychol), Australian Psychological Society (MAPS) e Chartered Scientist 
          (CSci) reconhecido pelo Science Council. Atualmente trabalho na School of Psychological Sciences na Birkbeck, University of 
          London (Reino Unido). Há mais de dez anos investigo comportamentos aditivos emergentes, como a perturbação do jogo 
          electrónico, a dependência das redes sociais, e a perturbação do jogo de azar.
          {style="text-align: center;"}
          
          Concluí o meu doutoramento da Nottingham Trent University no Reino Unido e publiquei mais de 100 estudos (ver o meu perfil 
          **[ResearchGate](https://www.researchgate.net/profile/Halley-Pontes)** para uma lista completa) em várias revistas científicas e 
          apresentei o meu trabalho de investigação em  várias conferências internacionais. A minha investigação recebeu o prémio Durand 
          Jacobs Award da McGill University (Canadá) e com o Early Career Research Award da Australian Psychological Society (Austrália) 
          pelas contribuições à  psicologia dos comportamentos aditivos e para a ciberpsicologia.
          {style="text-align: center;"}

          A minha **[Chave Pública PGP](https://drive.proton.me/urls/GYZNM1652C#C34xqQi4LYoU)** fingerprint é: DE26 2BED FB0D C0ED 97F7 
          DD95 234E 9809 AEDA EAC8.
          {style="text-align: center;"}
          
    design:
      columns: '1'
  - block: collection
    content:
      title: Últimos posts
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