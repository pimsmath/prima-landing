---
title: 'Home'
date: 2025-03-18
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: hero
    content:
      title: Pacific Rim Mathematical Association <div id="prima-hero-logo">![](PRIMALogo_0.png)</div> 环太平洋数学协会
      text: The Pacific Rim Mathematical Associate (PRIMA) is a network of
       mathematical scientists and leading mathematical organizations which
       promotes collaboration and career development for Mathematical Scientists
       around the Pacific rim.
      primary_action:
        text: PRIMA Congress
        url: /#congress
      secondary_action:
        text: Members
        url: /members
        icon: rocket-launch
      #announcement:
      #  text: "Summarising PRIMA 2021."
      #  link:
      #    text: "Read more"
      #    url: "/blog/"
    design:
      spacing:
        padding: [0, 0, 0, 0]
        margin: [0, 0, 0, 0]
      # For full-screen, add `min-h-screen` below
      css_class: "light"
      background:
        color: '#C5DAC6'
        #image:
        #  # Add your image background to `assets/media/`.
        #  filename: bg-triangles.svg
  - block: markdown
    id: congress
    content:
      title: PRIMA Congress
      text: The PRIMA Congress is the flagship activity of PRIMA. It was created
        to create rich networking possibilities, survey regional mathematical
        developments, and disseminate the latest scientific advances. The congress
        is held every four years, see below for details.
    design:
      spacing:
        padding: [6rem, 0, 0, 0]
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900 text-center"
  - block: cta-image-paragraph
    id: congress-instances
    content:
      title: PRIMA Congress
      items:
        - title: PRIMA 2022
          text: Vancouver, Canada
          feature_icon: star
          features:
            - "December 4-9, 2022"
          # Upload image to `assets/media/` and reference the filename here
          image: prima2022.png
          button:
            text: More Details
            url: /congress/prima2022
        - title: PRIMA 2017
          text: Oaxaca, Mexico
          feature_icon: star
          features:
            - "August 14-18, 2017"
          # Upload image to `assets/media/` and reference the filename here
          image: prima2017.png
          button:
            text: More Details
            url: /congress/prima2017/
        - title: PRIMA 2013
          text: Shanghai, China
          feature_icon: star
          features:
            - "June 23-28, 2013"
          button:
            text: More Details
            url: /congress/prima2013/
          # Upload image to `assets/media/` and reference the filename here
          image: prima2013.jpg
        - title: PRIMA 2009
          text: Syndey, Australia
          feature_icon: star
          features:
            - "July 6-10, 2009"
          # Upload image to `assets/media/` and reference the filename here
          image: prima2009.jpg
          button:
            text: More Details
            url: /congress/prima2009/
    design:
      # Section background color (CSS class)
      spacing:
        padding: [0, 0, 6rem, 0]
      css_class: "bg-gray-100 dark:bg-gray-900"
      columns: '1'
      view: showcase
      flip_alt_rows: false
  - block: markdown
    id: about
    content:
      title: About PRIMA
      text: The representatives of a number of leading mathematical institutions
        in the Pacific Rim met at the Banff International Research Station, Canada
        on October 14-15, 2005. The rapidly expanding scientific capacity and the
        enormous potential arising from the cultural and intellectual diversity of
        the Pacific Rim region were recognized. It was agreed that a well
        coordinated and concerted effort among our institutions and countries
        would stimulate a vibrant and interconnected mathematical community whose
        activities would have an unprecedented impact on our economic, social and
        cultural development. A resolution was made to establish an organization,
        to be known as the Pacific Rim Mathematical Association (PRIMA), and to
        develop an action plan to achieve these goals. The mission of PRIMA is to
        promote and facilitate the development of the mathematical sciences
        throughout the Pacific Rim region. The principal objectives of PRIMA are

        * To create a network for the exchange of ideas and the dissemination
          of scientific knowledge

        * To coordinate and encourage wider participation in scientific
          activities in the region in order to maximize their effectiveness;

        * To substantially increase the region's capacity in training the next
          generations of mathematical scientists;

        * To identify geographical areas in need of mathematical advancement
          and to assist them in strengthening their expertise and
          infrastructure;

        * To promote breadth and diversity within the mathematical sciences
          community;

        * To share expertise in the promotion of the mathematical sciences,
          and their impact on society and the global economy;

        * To pool resources where appropriate, and to identify potential new
          ones to assist the scientific development of every community in our
          region.
    design:
      columns: '1'
      view: showcase
---
