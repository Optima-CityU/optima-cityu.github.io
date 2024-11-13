---
# Leave the homepage title empty to use the site title
title:
date: 2024-10-24
type: landing

sections:
  - block: hero-with-stats
    content:
      title: Optima Group
      text: "**BUILD THE FUTURE TOGETHER WITH AI**"
      details: "Colledge of Computing, \n\n[City University of Hong Kong](https://cityu.edu.hk)"
      primary_action:
        text: See what we're doing
        url: news/
        icon: arrow-up-right
      items:
        - name: "Room"
          description: "G7315"
        - name: "Building"
          description: "YEUNG"
        - name: "Street"
          description: "83 Tat Chee Avenue"
        - name: "Region"
          description: "China Hong Kong SAR"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "bg-gradient-to-r from-rose-100 to-teal-100"
#      background:
#        color: ""
#        image:
#          # Add your image background to `assets/media/`.
#          filename: ""
#          filters:
#            brightness: 1.0
  - block: stats
    content:
      items:
        - statistic: "29"
          description: |
            Members
        - statistic: "386+"
          description: |
            Publications
        - statistic: "41000+"
          description: |
            Citations
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: group-vision
    content:
      title: ""
      text: ""
      items:
        - name: "Qingfu ZHANG"
          role: "Chair Professor of Optima Group"
          # Upload image to `assets/media/` and reference the filename here
          image: members/qingfuzhang.jpg
          text: "We should understand the value of our own work in a broad sense!"
    design:
      spacing:
        # Reduce bottom spacing so the testimonial appears vertically centered between sections
        padding: ["1 rem", 0, 0, "1 rem"]
  - block: cta-image-paragraph
    id: Selected Researches
    content:
      items:
        - title: Few for Many
          text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          # Upload image to `assets/media/` and reference the filename here
          image: selected_researches/conference-headway-F2KRf_QfCqw.jpg
          button:
            text: Learn More
            url: selected_researches/1
        - title: Automatic Algorithm Design with LLMs
          text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          # Upload image to `assets/media/` and reference the filename here
          image: selected_researches/conference-headway-F2KRf_QfCqw.jpg
          button:
            text: Learn More
            url: selected_researches/2
        - title: Evolutionary Optimization
          text: Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
          # Upload image to `assets/media/` and reference the filename here
          image: selected_researches/conference-headway-F2KRf_QfCqw.jpg
          button:
            text: Learn More
            url: selected_researches/3
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      spacing:
        padding: [0, 0, 0, 0]
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: news
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: ["1 rem", 0, 0, 0]
  - block: logos
    content:
      title: "Collaborators"
      text: "Together We Stand!"
      # Image path relative to assets/media/ folder
      logo_folder: 'collaborator/'
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""
  - block: newsletter
    content:
      title: "Stay up to date"
      text: "Be the first to receive updates such as new publications, events, and ideas."
      text_cta: "Sign up to our newsletter 🔥"
      button:
        text: "Subscribe"
      convertkit:
        form_id: ''
        msg_subscribed: "Success! Please check your email to confirm your subscription."
    design:
      card:
        # Card background color (CSS class)
        css_class: "bg-primary-700"
        css_style: ""

---
