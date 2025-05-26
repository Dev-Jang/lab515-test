---
# Leave the homepage title empty to use the site title
title: LAB515
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        LAB515
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        Lab515은 한양대학교 경영대학 이상용 교수님이 이끄는 MIS(경영정보시스템) 및 BI(비즈니스 인포매틱스) 분야의 연구실입니다.
  
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
      title: Latest Preprints
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
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
