[andre601]: https://github.com/Andre601
[discord]: https://discord.gg/2a9VC4AK6x
[contributing]: https://github.com/Readme-Workflows/Readme-Icons/blob/main/CONTRIBUTING.md


# Readme-Icons
> Currated by [@Andre601][andre601]

[![CDN hits](https://data.jsdelivr.com/v1/package/gh/Readme-Workflows/Readme-Icons/badge)](https://www.jsdelivr.com/package/gh/Readme-Workflows/Readme-Icons)

Welcome to the Readme-Icons Repository!  
This Repository aims to provide various SVG icons to use in your Readme, or any other markdown file.

## Table of Contents

- [How to use](#how-to-use)
  - [Specific versions](#specific-versions)
- [Licenses](#licenses)
- [Why use this and not the actual source?](#why-use-this-and-not-the-actual-source)
- [Icons](#icons)
  - [Gifs](#gifs)
  - [Octicons](#octicons)
- [Submit Icons](#submit-icons)

## How to use
We keep all our icons/images in a `icon` directory, where they are further split up into categories.

The easiest way to use the icons is to use JSDelivr for it.  
Simply visit https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@main/icons/ open the respective folder, click on the name of the Icon you want to use and copy your current URL from your browser.

This link can then be used through Markdown's image-link format (`![text](:link)`) or through the reference link-syntax (`[text]: :link`) to then use in multiple places with `![text]`

### Specific versions
Thanks to releases can you also use specific versions for your icons.  
This is useful if your icon got changed or even removed but you still want to use it.

To use specific versions, replace `main` in `Readme-Icons@main` with the version you would like to use (i.e. `Readme-Icons@v1.0.0`).  
Keep in mind that there needs to be a valid Release on this Repository for this to work!

## Licenses

Please note that the different icons may have different licenses. Each folder in the `icons` directory is equipped with a copy of the respective license(s) used.

## Why use this and not the actual source?

There are multiple reasons to use this over the existing sources:

1. **Recoloured SVGs**  
   There is no easy way to recolour existing SVG icons without manipulating their `<svg>` or `<path>` tags, especially with markdown-syntaxes.  
   Here, the icons have receieved new colours where needed to represent their common use place. This allows you to have coloured SVG icons without much work.
2. **Single Source**
   Thanks to this Repository will you only have a single source you need to use compared to other places. This reduces the need of maintainability a lot as you don't have to worry about the source suddenly changing or even being gone.  
3. **Safe**  
   Using this Repository over the source is much more save, as we won't remove existing SVG icons without any prior notice.  
   Each Icon change or removal is done through Pull request and mentioned in any possible release on this Repository.

If you have any further questions or just want to get in touch with us, join our [Discord Server][discord].

## Icons
The icons are split up into different categories.  
Each category has their own README file with the icons listed.

### Gifs
Collection of 16x16 gifs you can use in your README.

> [To the category][categoryGifs]

[categoryGifs]: https://github.com/Readme-Workflows/Readme-Icons/tree/main/icons/gifs

### Octicons
GitHub's own Set of SVG icons.

> [To the category][categoryOcticons]

[categoryOcticons]: https://github.com/Readme-Workflows/Readme-Icons/tree/main/icons/octicons

## Submit Icons

Do you want to add some icons to this Repository?  
If yes, make sure to follow the basic guidelines in our [Contributing file][contributing].
