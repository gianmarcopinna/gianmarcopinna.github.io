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
      text:
        <div class="container">  <div class="row">   <div      class="section-heading col-12 col-lg-4 mb-3 mb-lg-0 d-flex flex-column     align-items-center align-items-lg-start">    </div>    <div class="col-12 col-lg-8">      <p>Feel free to reach out via one of the following options:</p>      <ul class="fa-ul">
        <div class="flex gap-4 items-center"><svg style="height:1.5rem;" xmlns="http://www.w3.org/2000/svg"
        viewBox="0 0 24 24">
        <path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="1.5"
        d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75">
        </path>
        </svg><span id="person-email"><a
        href="mailto:gianmarco.pinna@uniroma2.it">gianmarco.pinna@uniroma2.it</a></span></div>
        <div class="flex gap-4 items-center"><svg style="height:1.5rem" viewBox="0 0 512 512">
        <path fill="currentcolor"
        d="M389.2 48h70.6L305.6 224.2 487 464H345L233.7 318.6 106.5 464H35.8L200.7 275.5 26.8 48H172.4L272.9 180.9 389.2 48zM364.4 421.8h39.1L151.1 88h-42L364.4 421.8z">
        </path>
        </svg><span id="person-email"><a
        href="https://www.linkedin.com/in/gian-marco-pinna-853709b6">https://www.linkedin.com/in/gian-marco-pinna-853709b6</a></span></li>     </ul>    </div>  </div></div>
---
