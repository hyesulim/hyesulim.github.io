---
title: Home
date: 2026-04-09
type: landing

sections:
  - block: hero
    content:
      title: Hyesu Lim, PhD
      text: >-
        **Postdoctoral researcher at Helmholtz Munich**<br>
        I build interpretability tools for vision, language, and multimodal
        models — aiming for AI systems that are testable, explainable, and
        controllable.
      primary_action:
        text: View Publications
        url: /#publications
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
        I study how deep learning models — vision, language, and multimodal —
        represent concepts, and develop interpretability tools, especially
        sparse autoencoders, that expose what these models learn.

        My goal is to build AI systems that are **testable, explainable, and
        controllable**, so that people can understand, trust, and interact
        with them more naturally. I apply these methods across scientific
        domains, from medical imaging to language, bridging interpretability
        research with real-world use.

        This site collects selected publications and notes.
    design:
      columns: '1'
      spacing:
        padding: ["2rem", "0", "1rem", "0"]

  - block: publications-list
    id: publications
    content:
      title: Publications
      subtitle: Selected publications. For the full list, see my <a href="https://scholar.google.com/citations?user=CqRG8v0AAAAJ&hl=en" target="_blank" rel="noopener">Google Scholar</a>.
    design:
      spacing:
        padding: ["1rem", "0", "1rem", "0"]

  - block: markdown
    id: connect
    content:
      title: Contact
      text: |
        The easiest way to reach me is by email.

        - <i class="fas fa-envelope" aria-hidden="true"></i> hyesulim.ac@gmail.com
        - <i class="fab fa-github" aria-hidden="true"></i> [github.com/hyesulim](https://github.com/hyesulim)
        - <i class="fab fa-linkedin" aria-hidden="true"></i> [linkedin.com/in/hyesulim](https://linkedin.com/in/hyesulim)
        - <i class="fas fa-graduation-cap" aria-hidden="true"></i> [Google Scholar](https://scholar.google.com/citations?user=CqRG8v0AAAAJ&hl=en)
    design:
      columns: '1'
      spacing:
        padding: ["1rem", "0", "4rem", "0"]
---
