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
        - statistic: "135+"
          description: |
            Publicações
        - statistic: "19,000+"
          description: |
            Citações
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
          {{% callout warning %}}
          **A tradução do site para o Português ainda está a ser finalizada**
          {{% /callout %}}

          Sou psicólogo filiado à British Psychological Society (CPsychol), Australian Psychological Society (MAPS) e Chartered Scientist 
          (CSci) reconhecido pelo Science Council. Atualmente trabalho na School of Psychological Sciences na Birkbeck, University of 
          London (Reino Unido). Há mais de dez anos investigo comportamentos aditivos emergentes, como a perturbação do jogo 
          electrónico, a dependência das redes sociais, e a perturbação do jogo de azar.
          {style="text-align: center;"}
          
          Concluí o meu doutoramento da Nottingham Trent University no Reino Unido e publiquei mais de 100 estudos em várias revistas científicas
          (ver o meu perfil **[ResearchGate](https://www.researchgate.net/profile/Halley-Pontes)** para uma lista completa).
          {style="text-align: center;"}
          
          Recentemente, fui incluído na **[Lista Mundial dos 2% Melhores Cientistas da Stanford-Elsevier de 2026](https://elsevier.digitalcommonsdata.com/datasets/btchxktzyw/9)**.
          Previamente, a minha investigação também recebeu o prémio Durand Jacobs Award da McGill University (Canadá) e o Early Career Research Award da Australian Psychological
          Society (Austrália) pelas contribuições à psicologia dos comportamentos aditivos e para a ciberpsicologia.
          {style="text-align: center;"}

          A minha **[Chave Pública PGP](https://drive.proton.me/urls/GYZNM1652C#C34xqQi4LYoU)** fingerprint é: DE26 2BED FB0D C0ED 97F7 
          DD95 234E 9809 AEDA EAC8.
          {style="text-align: center;"}
          
    design:
      columns: '1'
  - block: collection
    content:
      title: Última publicação
      subtitle: ''
      text: ''
      page_type: post
      count: 1
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      offset: 0
      order: desc
      archive:
        enable: true
        text: Ver todas
        link: /pt/post/
    design:
      view: list
      spacing:
        padding: [0, 0, 0, 0]
---