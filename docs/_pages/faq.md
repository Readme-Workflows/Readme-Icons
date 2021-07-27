---
layout: splash
permalink: /faq/

title: "FAQ"
excerpt: "Collection of commonly asked questions about Readme-Icons."

toc: true

header:
  overlay_color: "#0d1117"
  actions:
    - label: "<i class='fab fa-discord'></i> Ask us more on Discord!"
      url: "https://discord.gg/2a9VC4AK6x"
---

# Why should I use this?
You don't have to use the icons offered here, but doing so will have benefits compared to f.e. using the direct source of an icon:

- **Better control about what icon you want to use.**  
  Don't like that icon X was removed or changed? Just use a specific version or even commit hash to use the same icons, even when they changed in later version.
- **Coloured SVG icons**  
  There is no simple way of changing the colours of an SVG icon and most pages offer their icons in a neutral (white) colour which is not always optimal.  
  We changed the colours of the SVG icons to make sure that they are visible in both light and dark theme without any extra work for you. Our colours are often based on the source's usage of these icons.

# How can I use the icons?
We provide the Icons through [JSDelivr](https://jsdelivr.net).

In order to use the icons, can you use the following Base-URL:  
> https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/

Each set of icon is located within its own folder, allowing you an easier finding of them.  
The easiest way to get the full URL of an Icon would be to click the above URL, followed by the folder where the icon is located in and finally the icon you want to use.

# What about specific versions?
That's easy. Just use the [above mentioned URL](#how-can-i-use-the-icons) and replace `main` with either a [Release Tag]() or a Commit hash.

Examples:

- https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/ApprovedChanges.svg
- https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@827a261/icons/octicons/ApprovedChanges.svg

# Can I suggest new icons?
You sure can!

Just head over to the [GitHub Repository](https://github.com/Readme-Workflows/Readme-Icons) and PR the new icons.  
When you do that, follow the Pull request template and also make sure that you understand our [Version Policy](https://github.com/Readme-Workflows/Readme-Icons/blob/main/VERSION_POLICY.md).