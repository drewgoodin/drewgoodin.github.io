---
layout: splash
title: Welcome
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /assets/images/autumn.jpg
  caption: "Artwork credit: [Jeff Ostberg](https://jeffostberg.se/)"
  actions:
    - label: "Resume (PDF)"
      url: "/assets/files/resume-goodin.pdf"
excerpt: "Thanks for checking out my site."
features: 
  - excerpt: "Some things of mild interest:"
feature_row:
  - image_path: "/assets/images/recipes.jpg"
    url: "/cookbook"
    title: "Food"
    excerpt: "A growing collection of things I enjoy cooking."
    btn_label: "Go"
    btn_class: "btn--inverse"
  - image_path: "/assets/images/github.jpg"
    url: "https://github.com/drewgoodin"
    title: Code 
    excerpt: "My personal projects. Mostly Perl."
    btn_label: "Go"
    btn_class: "btn--inverse"
  - image_path: "/assets/images/windowtailor.jpg"
    url: "https://thewindowtailor.com"
    title: "Work"
    excerpt: "The Window Tailor, my 9-to-5 (usually)."
    btn_label: "Go"
    btn_class: "btn--inverse"
---

{% include feature_row id="features" type="center" %}

{% include feature_row  %}
