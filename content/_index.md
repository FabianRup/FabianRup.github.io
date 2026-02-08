---
# Leave the homepage title empty to use the site title
title: ''
date: 2025-10-10
type: landing

design:
  # Default section spacing
  spacing: '2rem'

sections:
  - block: resume-biography-3
    id: bio
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ''
    design:
      # Apply a gradient background
      css_class: hbx-bg-gradient
      # Avatar customization
      avatar:
        size: large # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: Here is a selection of projects that I am currently working on.
      filters: { folders: [projects] }
    design:
      view: article-grid
      columns: 2
      fill_image: false

  - block: collection
    id: news
    content:
      title: Recent News
      text: Updates on conferences, talks, publications, field trips, and fun stuff.
      filters: { folders: [news] }
    design:
      view: article-grid
      columns: 3
      fill_image: false

  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3

      # === Experience ===
  - block: resume-experience
    id: experience
    content:
      title: Experience
      username: admin
    design:
      date_format: 'January 2006'
      is_education_first: false

  # === Awards ===
  - block: resume-awards
    content:
      title: Fellowships and Awards
      username: admin

  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation

---
