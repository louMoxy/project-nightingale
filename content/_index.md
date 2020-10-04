---
layout: blocks
title: Homepage
page_sections:
- template: text-only-hero-banner
  block: text-only-hero-banner
  heading: "<strong>Text only hero banner!</strong>"
  backgroundColor: red
- template: hero-banner-w-image
  block: hero-banner-w-image
  background_image: "/uploads/logo-516c18ef04e0eead60f85595d9f8b56a.png"
  headline: Hero banner with image -  Headline
  content: Content
  cta:
    link_text: CTA
    enabled: true
    link_url: "/"
- template: detail-content
  block: text-1
  headline: Detail Content - Headline
  content: Detail Content - Content
- template: 1-column-text
  block: one-column-1
  headline: 1 column text Headline
  content: 1 column text
- template: 2-column-text
  block: two-column-1
  col_1:
    headline: '2 column text '
    content: '2 column text '
  col_2:
    headline: 2 column text
    content: 2 column text
- template: 3-column-text
  block: three-column-1
  col_1:
    headline: 3 column text
    content: 3 column text
  col_3:
    headline: 3 column text
    content: 3 column text
  col_2:
    headline: 3 column text
    content: 3 column text
- template: full-width-media-element
  block: media-1
  image: "/uploads/logo-516c18ef04e0eead60f85595d9f8b56a.png"
- template: 2-column-media-element
  block: media-2
  image_1:
    image: "/uploads/logo-516c18ef04e0eead60f85595d9f8b56a.png"
  image_2:
    image: "/uploads/logo-516c18ef04e0eead60f85595d9f8b56a.png"
- template: signup-bar
  block: cta-bar
  content: Sign up
  email_recipient: louisemoxy@gmail.com

---
