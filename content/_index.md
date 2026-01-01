---
title: 'TMLr'
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
        url: "/browse/century"
        icon: rocket-launch
      secondary_action:
        text: About the Project
        url: "/about/"
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
        - title: "Mission"
          text: "The _Thesaurus Musicarum Latinarum Revivificatus_ (TMLr) aims to give free access to and make searchable Latin texts on music from the late antiquity to the seventeenth century, in transcriptions from original sources and public-domain editions. Primarily an aid to musicological research, this resource aims also to assist anyone interested in documenting the broader intersections of music with the humanities and the sciences within the Western tradition."
          feature_icon: check
          features: ""
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
        - title: "Access"
          text: "The TMLr is a repository of public-domain materials. Please note that the original _Thesaurus Musicarum Latinarum_ also included copyrighted materials by permission of the copyright holders. The TMLr provides external links to those copyrighted materials when possible, but it does not have permission to reproduce them directly."
          feature_icon: bolt
          features: ""
          # Upload image to `assets/media/` and reference the filename here
          image: coffee.jpg
          button:
            text: Copyright Notice
            url: "/TMLr/copyright/"
        - title: "History"
          text: "The original _Thesaurus Musicarum Latinarum_ was created in 1990 as the inaugural project of the Center for the History of Music Theory and Literature (CHMTL), and it was long supported by Indiana University and the Jacobs School of Music. An unfortunate history of cyber attacks, funding cuts, and website issues has revealed the pitfalls of relying on a single host for this valuable resource. Consequently, the TMLr aims to reproduce the public-domain materials, while also updating the user experience."
          feature_icon: check
          features: ""
          # Upload image to `assets/media/` and reference the filename here
          image: build-website.png
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
  
---