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
        </svg><span id="person-twitter"><a href="https://x.com/GianMarcoPinna">https://x.com/GianMarcoPinna</a></span>
        </div>
        <div class="flex gap-4 items-center"><svg style="height:1.5rem" height="1em" viewBox="0 0 448 512"><path fill="currentcolor" d="M416 32H31.9C14.3 32 0 46.5.0 64.3v383.4C0 465.5 14.3 480 31.9 480H416c17.6.0 32-14.5 32-32.3V64.3c0-17.8-14.4-32.3-32-32.3zM135.4 416H69V202.2h66.5V416zm-33.2-243c-21.3.0-38.5-17.3-38.5-38.5S80.9 96 102.2 96c21.2.0 38.5 17.3 38.5 38.5.0 21.3-17.2 38.5-38.5 38.5zm282.1 243h-66.4V312c0-24.8-.5-56.7-34.5-56.7-34.6.0-39.9 27-39.9 54.9V416h-66.4V202.2h63.7v29.2h.9c8.9-16.8 30.6-34.5 62.9-34.5 67.2.0 79.7 44.3 79.7 101.9V416z"></path></svg><span id="person-email"><a
        href="https://www.linkedin.com/in/gian-marco-pinna-853709b6">https://www.linkedin.com/in/gian-marco-pinna-853709b6</a></span></li>     </ul>    </div>  </div></div>
---
