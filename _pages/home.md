---
layout: splash
permalink: /
hidden: true
title: Em desenvolvimento
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/bg3.jpg
  actions:
    - label: "<i class='fas fa-download'></i> Install now"
      url: "/docs/quick-start-guide/"
excerpt: > 
  A flexible two-column Jekyll theme. Perfect for building personal sites, blogs, and portfolios.<br />
  <small><a href="https://github.com/mmistakes/minimal-mistakes/releases/tag/4.23.0">Latest release v4.23.0</a></small>
feature_row:
  - image_path: /assets/images/Rlogo.png
    alt: "customizable"
    title: "R"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/pythonlogo.jpg
    alt: "fully responsive"
    title: "Python"
    excerpt: "Built with HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /assets/images/powerbilogo.png
    alt: "100% free"
    title: "Power BI"
    excerpt: "Free to use however you want under the MIT License. Clone it, fork it, customize it... whatever!"
    url: "/docs/license/"
    btn_class: "btn--primary"
    btn_label: "Learn more"      
---


{% assign post = site.posts.first %}
<h3>{{ site.title }}</h3>
<h3>{{ seo_title }}</h3>
<h3>{{ page.title }}</h3>

<a href="{{ post.url }}">Clique aqui</a>
<p class="blogdate">{{ post.date | date: "%d %B %Y" }}</p>
<div>{{ post.excerpt }}</div>






{% include feature_row %}





