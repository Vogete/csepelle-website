---
title: 'Home'
date: 2025-11-16

type: landing

design:
  # Default section spacing
  spacing: "1rem"

sections:
  - block: hero
    content:
      title: Csepel Lövész Egylet
      image:
        filename: coffee.jpg
      text: |- 
        **Üdvözöljük honlapunkon!**
      # primary_action:
      #   text: Get Started
      #   url: https://hugoblox.com/templates/
      #   icon: rocket-launch
      # secondary_action:
      #   text: Read the docs
      #   url: https://docs.hugoblox.com
      # announcement:
      #   text: "Announcing the release of version 1."
      #   link:
      #     text: "Read more"
      #     url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below (these are css classes)
      css_class: "dark hero-blur-bg"
      background:
        image:
          # Add your image background to `assets/media/`.
          filename: loter.png
          size: cover
          parallax: false
  - block: cta-image-paragraph
    id: bemutatkozas
    content:
      title: Bemutatkozás
      items:
        - title: Légfegyveres lövészet
          text: |-
            A Csepel SC. területén található a 10 méteres légfegyveres lőpályánk. 
            A légpisztolyos és légpuskás versenyszámok gyakorlásához nyújt ideális környezetet, ahol edzői segítséggel a szabadidős sportolók kikapcsolódásképpen űzhetik hobbijukat és a leigazolt versenyzőink készülhetnek fel versenyeikre.

          image: build-website.png
        - title: Tűzfegyveres lövészet
          text: A 25 méteres lőpályánk egyaránt alkalmasa kis és nagykaliberű lővészet számára.
                <br>
                A lőállások elektronikus lőlapmozgató berendezéssel vannak ellátva.
          image: coffee.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-blue-50 dark:bg-blue-900"
---
