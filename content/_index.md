---
# Leave the homepage title empty to use the site title
title:
date: 2024-06-16
type: landing

sections:
  - block: hero
    content:
      title: |
        TZL Coffee
      image:
        filename: welcome.png
      text: |
        <br>
        
        Welcome to TZL Coffee, your neighborhood haven for exquisite coffee and refreshing beverages, founded since 2024. At our café, we take pride in crafting the perfect cup of coffee, whether you prefer a bold Americano or a smooth and indulgent specialty latte. Our menu also features a delightful selection of floral teas and sparkling soft drinks, ensuring there's something for everyone.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: promo.png
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen

  # - block: collection
  #   content:
  #     title: Latest Preprints
  #     text: ""
  #     count: 5
  #     filters:
  #       folders:
  #         - publication
  #       publication_type: 'article'
  #   design:
  #     view: citation
  #     columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
