---
title: Home
date: 2026-04-09
type: landing

sections:
  - block: hero
    content:
      title: Hyesu Lim, PhD
      text: >-
        Postdoctoral researcher at Helmholtz Munich working on machine
        learning interpretability.
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
        I am a machine learning researcher working on interpretability, with the
        goal of building testable, explainable, and controllable AI systems.

        My work focuses on narrowing the gap between state-of-the-art AI and
        real-world use cases, making these systems easier for people to
        understand, trust, and interact with.

        This site collects selected projects, notes, and writing.
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

        - Email: hyesulim.ac@gmail.com
        - GitHub: [github.com/hyesulim](https://github.com/hyesulim)
        - LinkedIn: [linkedin.com/in/hyesulim](https://linkedin.com/in/hyesulim)
    design:
      columns: '1'
      spacing:
        padding: ["1rem", "0", "4rem", "0"]
---
