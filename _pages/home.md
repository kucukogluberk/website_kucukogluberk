---
title: "Hey there!"
layout: home
permalink: /
#author_profile: false
header:
  overlay_color: "#333"
  overlay_filter: "0.5"
  overlay_image: /assets/images/welcome.jpg
  actions:
    - label: "Home"
      url: /
    - label: "About"
      url: /about/
    - label: "Blog"
      url: /blog/
    # - label: "Projects"
    #   url: /projects/
    - label: "Tools"
      url: /tools/
    - label: "Contact"
      url: /contact/
    - label: "CV"
      url: /cv/
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Welcome to my website. Hope you find what you're looking for!"
intro:
  - excerpt: Hello! I’m Berk, a PhD student specializing in electron microscopy and computational imaging. In the About section, you can learn more about me and my academic journey and research interests. Check out my Blog for insights into my latest projects.
sidebar:
  - title: "Berk Kucukoglu"
    image: /assets/images/berkProfile_cropped.jpg
    image_alt: "logo"
    text: "Researcher / Amateur Radio Enthusiast / "
#   - title: "About me"
#     text: "Hello! I’m Berk, a PhD student specializing in electron microscopy and computational imaging. In the About section, you can learn more about me and my academic journey and research interests. Check out my Blog for insights into my latest projects."
# feature_row:
#   - image_path: /assets/images/placeholder_2.jpg
#     alt: "placeholder image 1"
#     title: "Placeholder 1"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
#   - image_path: /assets/images/placeholder_1.jpg
#     image_caption: "Image courtesy of [Unsplash](https://unsplash.com/)"
#     alt: "placeholder image 2"
#     title: "Placeholder 2"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
#     url: "/blog/"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
#   - image_path: /assets/images/unsplash-gallery-image-3-th.jpg
#     title: "Placeholder 3"
#     excerpt: "This is some sample content that goes here with **Markdown** formatting."
feature_row1:
  - image_path: /assets/images/capsidV.png
    alt: "placeholder image 2"
    title: "Research related"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Right aligned with `type="right"`'
    url: /about/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/output_improved.gif
    alt: "placeholder image 2"
    title: "GHI Estimation with Neural Networks"
    excerpt: 'Todo: GIF quality is down'
    url: blog/GHI_Estimation/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/placeholder_1.jpg
    alt: "placeholder image 2"
    title: "Art and music related"
    excerpt: 'This is some sample content that goes here with **Markdown** formatting. Left aligned with `type="left"`'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"

# feature_row4:
#   - image_path: /assets/images/unsplash-gallery-image-2-th.jpg
#     alt: "placeholder image 2"
#     title: "Placeholder Image Center Aligned"
#     excerpt: 'This is some sample content that goes here with **Markdown** formatting. Centered with `type="center"`'
#     url: "#test-link"
#     btn_label: "Read More"
#     btn_class: "btn--primary"
---

{% include feature_row id="intro" type="center" %}

{% include feature_row %}

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="right" %}

{% include feature_row id="feature_row4" type="center" %}

