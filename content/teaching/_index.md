---
title: Teaching
summary: My courses
type: landing

cascade:
  - _target:
      kind: page
    params:
      show_breadcrumb: true

sections:
  - block: collection
    id: teaching
    content:
      title: Teaching
      filters:
        folders:
          - teaching
    design:
      view: article-grid
      columns: 2
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: bg1.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
---
