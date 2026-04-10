---
title: Home
date: 2026-04-09
type: landing

sections:
  - block: hero
    content:
      title: Hyesu Lim, PhD
      text: >-
        Machine learning scientist
      primary_action:
        text: View Projects
        url: /projects/
      secondary_action:
        text: Read Writing
        url: /blog/
      announcement:
        text: Download CV
        link:
          text: PDF
          url: /uploads/cv.pdf
    design:
      spacing:
        padding: ["5rem", "0", "3rem", "0"]
      css_class: home-hero-minimal
      background:
        color: '#f8f7f2'

  - block: markdown
    id: about
    content:
      title: About
      subtitle: A short introduction
      text: |
        I am a researcher / engineer / designer focused on building useful,
        understandable, and elegant digital systems.

        My work spans product development, technical research, and communication.
        I care especially about clarity: clear ideas, clear interfaces, and clear
        writing.

        This site collects selected projects, notes, and essays.
    design:
      columns: '1'
      spacing:
        padding: ["2rem", "0", "1rem", "0"]

  - block: collection
    id: featured-projects
    content:
      title: Selected Work
      subtitle: A few things I’d like you to see first
      text: ''
      filters:
        folders:
          - projects
        featured_only: true
      count: 3
    design:
      view: article-grid
      columns: 3
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  - block: collection
    id: latest-writing
    content:
      title: Writing
      subtitle: Notes, essays, and updates
      filters:
        folders:
          - blog
      count: 3
    design:
      view: article-grid
      columns: 3
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  - block: markdown
    id: connect
    content:
      title: Contact
      text: |
        The easiest way to reach me is by email.

        - Email: hello@example.com
        - GitHub: [github.com/yourhandle](https://github.com/yourhandle)
        - LinkedIn: [linkedin.com/in/yourhandle](https://linkedin.com/in/yourhandle)
    design:
      columns: '1'
      spacing:
        padding: ["1rem", "0", "4rem", "0"]
---
