---
title: 'Home'
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Thesaurus Musicarum Latinarum Revivificatus
      text: Online archive of music theory in Latin, reborn.
      primary_action:
        text: Browse the Texts
        url: "/TMLr/browse/century"
        icon: rocket-launch
      secondary_action:
        text: About the Project
        url: "/TMLr/about/"
      announcement:
        text: "Now in beta testing."
    design:
    #   spacing:
    #     padding: [0, 0, 0, 0]
    #     margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "dark"
      background:
        color: "navy"
        image:
          # Add your image background to `assets/media/`.
          filename: bg-triangles.svg
          filters:
            brightness: 0.5
          size: cover
          position: center
          parallax: false
  - block: cta-image-paragraph
    id: solutions
    content:
      items:
        - title: A title
          text: As easy as 1, 2, 3!
          features:
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
        - title: Another title
          text: Join our large community on Discord - ask questions and get live responses
          feature_icon: bolt
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  - block: testimonials
    content:
      title: ""
      text: ""
      items:
        - name: "Hugo Smith"
          role: "Marketing Executive at X"
          # Upload image to `assets/media/` and reference the filename here
          image: "testimonial-1.jpg"
          text: "Awesome, so easy to use and saved me so much work with the swappable pre-designed sections!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["6rem", 0, 0, 0]
---