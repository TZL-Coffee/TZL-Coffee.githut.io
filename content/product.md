---
title: 'Products'
date: 2024-06-19
type: landing

design:
  # Section spacing
  spacing: '5rem'

# Page sections
sections:
  - block: collection
    id: coffee
    content:
      title: Coffee
      text: some description about the coffee
      filters:
        folders:
          - products\coffee
    design:
      view: article-grid
      fill_image: false
      columns: "3"
  - block: collection
    id: tea   
    content:
      title: Tea
      text: some description about the Tea
      filters:
        folders:
          - tea
    design:
      view: article-grid
      fill_image: false
      columns: 3
---
