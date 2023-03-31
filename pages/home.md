---
layout: home
permalink: "/"
title: "Bitfox"
description: "A family of technical experts changing the world bit by bit."
header_transparent: true
meta_title: "Bitfox - A little bit of everything."

hero:
  enabled: true
  heading: "Bitfox"
  sub_heading: "A family of technical experts changing the world bit by bit."
  text_color: "#FFFFFF"
  background_color: "#1d2830"
  background_gradient: true
  background_image: "/assets/images/gen/home/home-1-large.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: true
  fullscreen_desktop: false
  height: "400px"
  buttons:
    enabled: false
    list:
      - text: "Buy Now"
        url: "https://www.zerostatic.io/theme/jekyll-advance/"
        external: true
        fa_icon: false
        size: large # "small", "normal", "large"
        outline: false
        style: "light" # "light", "dark", "primary"
      - text: "Documentation"
        url: "https://www.zerostatic.io/docs/jekyll-advance/v2.0/"
        external: true
        fa_icon: false
        size: large
        outline: true
        style: "light"

services:
  enabled: false
  heading: "Our Services"
  sub_heading: ""
  limit: 6
  sort: "weight" # 'date'
  view_more_button_text: "View All Services"
  view_more_button_link: "/services"
  prevent_click: false

intro:
  enabled: true
  align: left
  image: "/assets/images/gen/content/content-5-thumbnail.webp"
  heading: "Welcome" 
  sub_heading: "We love to create digital solutions."
  features:
    enabled: true
    list:
      - text: "Software development"
        fa_icon: "fas fa-check"
      - text: "Electrical engineering"
        fa_icon: "fas fa-check"
      #- text: "Fully responsive and SEO optimised."
      #  fa_icon: "fas fa-check"
      #- text: "Multiple content types including services, projects, blog and more."
      #  fa_icon: "fas fa-check"
  buttons:
    enabled: true
    list:
      - text: "About Us"
        url: "/about"
        external: false
        fa_icon: ""
        size: large
        outline: false
        style: "primary"

partners:
  enabled: true
  limit: 5
  sort: "weight" # 'date'

projects:
  enabled: true
  heading: "Our Projects"
  sub_heading: ""
  limit: 2
  columns: 2
  sort: "weight" # 'date'
  view_more_button_text: "View All Projects"
  view_more_button_link: "/projects"
  prevent_click: false

outro:
  enabled: true
  align: center
  image: false
  heading: Any project idea's?
  sub_heading: "Feel free to contact us."
  features:
    enabled: false
    list:
      - text: "Contact"
        fa_icon: "fas fa-envelope-open-text"
  buttons:
    enabled: true
    list:
      - text: "Contact Us"
        url: "/about"
        external: false
        size: "large"

posts:
  enabled: true
  heading: "Latest Posts"
  sub_heading: ""
  limit: 3
  columns: 3
  sort: "weight" # 'date'
  view_more_button_text: "View All Posts"
  view_more_button_link: "/blog"
  prevent_click: false
---
