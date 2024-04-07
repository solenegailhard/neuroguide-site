---
title: Questions

type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 👋 Bienvenue sur notre site NeuroGuide
        content: Les neurosciences t'intéressent mais tu te noie un peu dans le flot d'information? Retrouve ci-dessous toutes les questions d'étudiants comme toi qui se questionnent sur les parcours, débouchés et autres!
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: Explore et apprends ☕️
        content: 'Lis les témoignages de professionels passionés dans le domaine!'
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: Centre aux questions
        content: 'Tu n'as pas trouvé la réponse à ta question ou t'aimerait en savoir plus, n'hésite pas à nous contacter :)'
        align: right
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: collection
    content:
      title: Questions
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
      page_type: questions
    design:
      view: community/depliant
      columns: '1'

---