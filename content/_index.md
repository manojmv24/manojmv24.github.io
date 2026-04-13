---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '0.5rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: https://docs.google.com/document/d/1j0riQwI-DZ1drDGgKCBOv25HujvYhbGD/edit?usp=sharing&ouid=106066607589782938361&rtpof=true&sd=true
        target: _blank
      headings:
        about: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true
      
      # Reduce top spacing
      spacing:
        padding: ['20px', '0', '20px', '0']

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  
  - block: resume-experience
    id: experience
    content:
      username: me
      title: Experience
    design:
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: incubation
    content:
      title: Incubation and Startup Funding
      filters:
        folders:
          - incubation
        featured_only: false
    design:
      columns: '2'
      view: article-grid
      
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: consultancy
    content:
      title: Consultancy Projects
      filters:
        folders:
          - consultancy
        featured_only: false
    design:
      columns: '2'
      view: article-grid
      
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: funded-projects
    content:
      title: Funded Projects
      filters:
        folders:
          - funded-projects
        featured_only: false
    design:
      columns: '2'
      view: article-grid
      
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: publications
    content:
      title: 📚 Journal Publications
      text: ""
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: conferences
    content:
      title: 🎤 Conference Publications
      text: ""
      filters:
        folders:
          - conference
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: book-chapters
    content:
      title: 📖 Book Chapters
      text: ""
      filters:
        folders:
          - book-chapter
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: edited-books
    content:
      title: 📚 Edited Books
      text: ""
      filters:
        folders:
          - edited-book
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: patents
    content:
      title: 🔬 Patents
      text: ""
      filters:
        folders:
          - patent
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: copyrights
    content:
      title: ©️ Copyrights
      text: ""
      filters:
        folders:
          - copyright
        exclude_featured: false
      count: 0
    design:
      view: citation
      columns: 1
      group_by: 'year'
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: memberships
    content:
      title: 🏛️ Professional Memberships
      filters:
        folders:
          - membership
        featured_only: false
    design:
      columns: '2'
      view: article-grid
      
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: foreign-visits
    content:
      title: ✈️ Foreign Visits for Research Interaction and Paper Presentation
      filters:
        folders:
          - foreign-visit
        featured_only: false
    design:
      columns: 2
      view: article-grid
      
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: collection
    id: awards
    content:
      title: 🏆 Best Research Paper Awards
      filters:
        folders:
          - awards
        featured_only: false
    design:
      columns: '3'
      view: article-grid
      fill_image: true
      spacing:
        padding: ['40px', '0', '40px', '0']
  
  - block: cta-card
    demo: true # Only display this section in the HugoBlox Kit demo site
    content:
      title: 👉 Build your own academic website like this
      text: |-
        This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

        <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

        Easily build anything with blocks - no-code required!

        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
      button:
        text: Get Started
        url: https://hugoblox.com/templates/
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
