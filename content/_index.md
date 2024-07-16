---
title: ''
date: 2023-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:

  - block: biography
    id: bio
    content:
      username: admin
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download Résumé
        url: uploads/resume.pdf
    design:
      banner:
        # Upload your cover image to the `assets/media/` folder and reference it here
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        # Customize the style of your biography text
        style: 'text-align: justify; font-size: 0.8em;'

  - block: community/my-education
    id: education
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'

  - block: community/my-experience
    id: experience
    content:
      username: admin
    design:
      # Hugo date format
      date_format: 'January 2006'

  - block: awards
    content:
      title: Achievements
      username: admin

  - block: collection
    content:
      title: Certificates
      text: I enjoy making things. Here are a selection of projects that I have worked on over the years.
      filters:
        folders:
          - certificate
    design:
      view: article-grid
      fill_image: false
      columns: 3

  - block: skills
    content:
      title: Skills & Hobbies
      username: admin

  - block: languages
    content:
      title: Languages
      username: admin
---
