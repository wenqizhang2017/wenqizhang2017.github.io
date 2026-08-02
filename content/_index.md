---
title: ""
date: 2022-10-24
type: landing
design:
  spacing: "6rem"
sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  - block: markdown
    content:
      title: Research
      subtitle: ''
      text: |-
        My research focuses on data-driven modeling and reinforcement learning for energy-efficient HVAC system control, with an emphasis on methods that can be validated in real buildings.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
---
