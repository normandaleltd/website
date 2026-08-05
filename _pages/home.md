---
layout: splash
title: " "
permalink: /
header:
  overlay_color: "#000"
  overlay_filter: "0.35"
  overlay_image: /assets/images/home-hero.jpg
hero_rotator:
  enabled: true
  interval_ms: 5500
  images:
    - /assets/images/van-1-1024x768.jpg
    - /assets/images/sector-motorsport.jpg
    - /assets/images/home-hero.jpg
    - /assets/images/sector-classic-historic.jpg
    - /assets/images/sector-industrial.jpg
    - /assets/images/sector-marine.jpg
    - /assets/images/service-24-7.jpg
intro:
  - excerpt: "Established for over 50 years, Normandale is one of the UK's most reputable motorsport paint finishing companies, delivering high-quality finishes across Formula 1, Formula 3, World Touring Cars, British Touring Cars and GT Cars. We also provide advanced refinishing solutions for aviation, industrial and marine applications, from one-off work to high-volume projects."
feature_row:
  - image_path: /assets/images/service-24-7.jpg
    alt: "24/7 operation"
    title: "24/7 Operation"
    excerpt: "Round-the-clock support for new and existing customers."
    url: "/operation-24-7/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/service-repair-work.jpg
    alt: "repair work"
    title: "Repair Work"
    excerpt: "Vehicle body repair and restoration with specialist alignment capability."
    url: "/repair-work/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
  - image_path: /assets/images/service-collection-delivery.jpg
    alt: "collection and delivery"
    title: "Collection and Delivery"
    excerpt: "Insured, covered, enclosed collection and delivery throughout the UK."
    url: "/collection-delivery/"
    btn_label: "Learn More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/sector-motorsport.jpg
    alt: "market sectors"
    title: "Market Sectors"
    excerpt: "Explore our specialist paint finishing work across motorsport, aerospace, composites, classic/historic, industrial and marine sectors."
    url: "/market-sectors/"
    btn_label: "Explore Sectors"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/home-hero.jpg
    alt: "contact us"
    title: "Need a quote? Want to speak to us?"
    excerpt: "Call +44 (0) 1327 871818 or email enquiries@normandaleproducts.com."
    url: "/contact/"
    btn_label: "Contact Us"
    btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row2" type="left" %}

{% include feature_row id="feature_row3" type="right" %}