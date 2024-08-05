---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    id: contacts
    content:
      title: Contacts
      subtitle: A subtitle
      text: <div class="container"><div class="row"><div class="section-heading col-12 col-lg-4 mb-3 mb-lg-0 d-flex flex-column align-items-center align-items-lg-start"></div><div class="col-12 col-lg-8"><p>Feel free to reach out via one of the following options.</p><ul class="fa-ul"><li><i class="fa-li fas fa-envelope fa-2x" aria-hidden="true"></i><span id="person-email"><a href="mailto:gianmarco.pinna@uniroma2.it">gianmarco.pinna@uniroma2.it</a></span>
---
