---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Biomedical Circuits and Systems Lab
      image:
        filename: welcome.jpg
      text: |
        <br>

        The Biomedical Circuits and Systems Lab develops low-power integrated circuits and systems for neural interfaces, wireless power and data transfer, neuromodulation, and bioelectronic systems.

        <span style="font-size: 0.95rem; color: #666;">
        Hanyang University
        </span>
  
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

  - block: collection
    content:
      title: Latest Journal Papers
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article-journal'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---