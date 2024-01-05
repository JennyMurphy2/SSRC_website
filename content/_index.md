---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: slider
    content:
      slides:
      - title: 
        content: 'The Sports Science Replication Centre is based in Dublin, Ireland. The intention of this centre is to create a worldwide, collaborative investigation into the replicability of research findings specific to the field of sports science using objective and transparent replication studies of current evidence. 
        
        {{< icon name="download" pack="fas" >}} Download our {{< staticref "uploads/SSRCleaflet.pdf" "newtab" >}}leaflet{{< /staticref >}}'
        align: left
        background:
          image:
            filename: welcome.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#666'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000

  - block: markdown
    content:
      title: Collaborators to the Sports Science Replication Centre
      subtitle:
      text: |
        {{< youtube XOOjLOdAXGI >}}
    design:
      columns: '2'

  - block: markdown
    content:
      title: Mission Statement
      subtitle:
      text: |
          To date, a host of research has identified concerns with the replication of psychological research, leading to the formation of projects and groups such as the Many Labs and the Reproducibility Project in Psychology. [STORK (Society for Transparency, Openness and Replication in Kinesiology)](https://www.storkin.org) is the leading group in Sports and Exercise Science to improve research practices in this field. [**Find out more.**](https://ssreplicationcentre.com/about) 
    design:
      columns: '2'

  - block: collection
    content:
      title: Featured Publications
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: publication
    design:
      view: compact
      columns: '2'

  - block: collection
    content:
      title: Featured Talk
      subtitle:
      text:
      count: 1
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: event
    design:
      view: compact
      columns: '2'

  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
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
      view: showcase
      columns: '1'
      flip_alt_rows: true

  - block: markdown
    content:
      title: What is Replication?
      subtitle:
      text: |
        **Check out our short video that gives a brief overview of replication and the need for it in the field of Sport Science.**
        
        {{< youtube Y3ns1hZcHvM >}}
    design:
      columns: '1'
      
  - block: portfolio
    id: projects
    content:
      title: 'Completed and Ongoing Replication Studies'
      subtitle: '*List will be updated as more studies are added to the Open Science Framework overall [project page.](https://www.doi.org/10.17605/OSF.IO/3VUFG)*'
      count: 5
      filters:
        folders:
          - replications
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
      buttons:
        - name: All
          tag: '*'
        - name: Biomechanics
          tag: Biomechanics
        - name: Physiology
          tag: Physiology
        - name: Strength and Conditioning
          tag: Strength and Conditioning
        - name: Nutrition
          tag: Nutrition
        - name: Injury Prevention
          tag: Injury Prevention
        - name: Sports Performace
          tag: Sports Performance
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '1'
      view: card
      # For Showcase view, flip alternate rows?
      #flip_alt_rows: true

  - block: slider
    content:
      slides:
      - title: 
        content: 
        align: center
        background:
          image:
            filename: tud.jpg
            filters:
              brightness: 1
          position: center
          color: '#666'
      - title: Lunch & Learn ☕️
        content: 'Share your knowledge with the group and explore exciting new topics together!'
        align: left
        background:
          image:
            filename: irc.jpg
            filters:
              brightness: 1
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '300px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: false
      # Duration of transition between slides (in ms)
      interval: 2000
---