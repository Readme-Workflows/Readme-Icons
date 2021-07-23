---
layout: splash
permalink: /

title: "Readme-Icons"
excerpt: "Collection of images to use in your Readme"

header:
  overlay_color: "#0d1117"
  actions:
    - label: "<i class='fab fa-discord'></i> Discord"
      url: "https://discord.gg/2a9VC4AK6x"
    - label: "<i class='fab fa-github'></i> Source Code"
      url: "https://github.com/Readme-Workflows/Readme-Icons"

feature_row_1:
  - image_path: /assets/images/previews/gifs.gif
    alt: "gifs"
    title: "Gifs"
    excerpt: "Animated Gifs to bring life to your Readme file."
    btn_label: "Gifs Icons Page"
    btn_class: "btn--light-outline"
    url: /icons/octicons/
  - image_path: /assets/images/previews/octicons.png
    alt: "octicons"
    title: "Octicons SVG"
    excerpt: "A collection of GitHub's official SVG icons, recoloured for your personal need."
    btn_label: "Octicons Icons Page"
    btn_class: "btn--light-outline"
    url: /icons/octicons/
  - image_path: /assets/images/previews/placeholder.png
    alt: "placeholder"
    title: "Coming soon"
    excerpt: "Do you know a set of icons that we should add? [Let us know!](https://discord.gg/2a9VC4AK6x)"
---

{% capture readme-replacer %}
Looking for a more easy way to use Readme-Icons in your README file?  
Try out [Readme-Replacer](https://github.com/Readme-Workflows/readme-replacer) a GitHub Action created by [Readme-Workflows](https://github.com/Readme-Workflows)!
{% endcapture %}

<div class="notice--success">
  <h2 class="no_toc">News</h2>
  {{ readme-replacer | markdownify }}
</div>

## What is Readme-Icons?
Readme-Icons is a collection of various image files (SVG, PNG, Gifs, etc.) which are designed to be used within your own Readme file.

## Licenses
Please keep in mind that the icons used are licensed under the original license of their source.  
At no point do we claim ownership of the icons offered.

## Icon Sets

{% include feature_row id="feature_row_1" %}
