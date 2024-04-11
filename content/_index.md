---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        NeuroGuide
      image:
        filename: cerveau_question.jpg
      text: |
        <br>
        
        The **NeuroGuide** is a website for student navigating the world of neurosciences, questionning what pathway to choose, what carriers existing. It was developped in April 2024 by 4 students of the Neuroscience Master of the University Lyon 1.
        Poopooopoooppoooo
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    content:
      title: Plus d'informations
      subtitle:
      text: |
        <details>
        <summary>Les neurosciences c'est quoi?</summary>

        Les neurosciences constituent un domaine multidisciplinaire de la science qui étudie le système nerveux, y compris sa structure, sa fonction, son développement, son évolution, ses troubles et ses mécanismes sous-jacents. Ce domaine englobe une vaste gamme de disciplines, allant de la biologie cellulaire et moléculaire à la psychologie et à la philosophie.

        </details>

---