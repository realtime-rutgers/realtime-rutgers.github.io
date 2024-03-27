---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Rutgers WINLAB
        REALTIME Research Project
      image:
        filename: venndiagram.png
      text: |
        <br>
        
        Our <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2148104">NSF RINGS program project</a> is about developing frameworks for real-time operation, online decision-making, and offline training of ML-based applications that must be resilient to data, application, user, and system changes.
  
  - block: collection
    content:
      title: News
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
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
