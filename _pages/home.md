---
title: "Hey there!"
layout: home
permalink: /
#author_profile: false
header:
  overlay_color: "#333"
  overlay_filter: "0.5"
  overlay_image: /assets/images/welcomeBanner.jpg
  actions:
    - label: "Home"
      url: /
    - label: "About"
      url: /about/
    - label: "Blog"
      url: /blog/
    - label: "Art"
      url: /art/
    - label: "Tools"
      url: /tools/
    - label: "Contact"
      url: /contact/
    - label: "CV"
      url: /cv/
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Welcome to my website. Hope you find what you're looking for!"
intro:
#   - excerpt: '<center>Hello! I’m Berk, a PhD student specializing in electron microscopy, data science, and computational imaging.<br>In the About section, you can learn more about me and my academic journey and research interests.<br>Check out my Blog for insights into my latest projects.</center>'
  - excerpt: "Welcome! I'm Berk, a passionate PhD student at the intersection of electron microscopy, data science, and computational imaging. My research focuses on pushing the boundaries of biological imaging through innovative techniques like ptychography.\n\nCurious about my journey? Explore my [About](/about/) page to learn more about my academic background and research interests. For a deep dive into my latest projects and insights, check out my [Blog](/blog/). From cutting-edge microscopy techniques to data analysis breakthroughs, I share it all there.\n\nLooking for specific tools or resources? Head over to my [Tools](/tools/) section, where I showcase software and methods I've developed. And if you're interested in my published work, you can find a comprehensive list on my [Publications](/publications/) page.\n\nFeel free to [connect with me](/contact/) if you have any questions or potential collaborations!"
sidebar:
  - title: "Berk Küçükoğlu"
    image: /assets/images/aboutBerk/berkProfile_cropped.jpg
    image_alt: "logo"
    text: "Researcher / HAM Radio Enthusiast / Electronics Tinkerer / On a quest to find non-scientific hobbies"
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
  - image_path: /assets/images/research_related/researchRelated.webp
    alt: "placeholder image 2"
    title: "Research related"
    excerpt: 'My research is mainly related to cryo-EM and diffractive imaging. Find everything about cool cryo-EM stuff'
    url: /about/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row2:
  - image_path: /assets/images/ghi_project/ghiProject_cropped_im00.jpg
    alt: "placeholder image 2"
    title: "GHI Estimation with Neural Networks"
    excerpt: 'We won the EPFL MICRO-573 course competition! Using raw images from two cameras, we estimate the Global Horizontal Irradiance'
    url: blog/GHI_Estimation/
    btn_label: "Read More"
    btn_class: "btn--primary"
feature_row3:
  - image_path: /assets/images/placeholders/placeholder_1.jpg
    alt: "placeholder image 2"
    title: "Art and music related"
    excerpt: 'Coming soon!'
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

<!-- {% include feature_row id="intro" type="center" %} -->
<!-- {% include feature_row id="intro" type="wide"%} -->
{% include feature_row id="intro" type="wide"%}

<!-- {% include feature_row %} -->

{% include feature_row id="feature_row1" type="right" %}

{% include feature_row id="feature_row2" type="right" %}

{% include feature_row id="feature_row3" type="right" %}

<!-- {% include feature_row id="feature_row4" type="center" %} -->