---
title: Questions
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: "👋 Bienvenue sur notre site NeuroGuide"
        content: "Les neurosciences t'intéressent mais tu te noie un peu dans le flot d'information? Retrouve ci-dessous les réponses à toutes tes questions"
        align: center
        background:
          image:
            filename: coders.jpg
            filters:
              brightness: 0.7
          position: right
          color: '#666'
      - title: "Explore & apprends ☕️"
        content: "Lis les témoignages de professionels passionnés!"
        align: left
        background:
          image:
            filename: contact.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: "Centre aux questions"
        content: ''
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
      subtitle: Trouveras-tu ta question?
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