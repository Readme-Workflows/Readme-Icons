[andre601]: https://github.com/Andre601
[contributing]: https://github.com/Readme-Workflows/Readme-Icons/blob/main/CONTRIBUTING.md
[licenseocticons]: https://github.com/Readme-Workflows/Readme-Icons/blob/main/icons/octicons/OCTICONS_LICENSE.txt
[licensetwemoji]: https://github.com/twitter/twemoji/blob/master/LICENSE

# Readme-Icons

> Currated by [@Andre601][andre601]

Welcome to the Readme-Icons Repository!  
This Repository aims to provide various SVG icons to use in your Readme, or any other markdown file.

## Table of Contents

- [Readme-Icons](#readme-icons)
  - [Table of Contents](#table-of-contents)
  - [How to use](#how-to-use)
    - [Specific versions](#specific-versions)
  - [Licenses](#licenses)
  - [Why use this and not the actual source?](#why-use-this-and-not-the-actual-source)
  - [Icons](#icons)
    - [Octicons](#octicons)
      - [Issues](#issues)
      - [Pull requests](#pull-requests)
      - [Miscelanious](#miscelanious)
    - [Gifs](#gifs)
  - [Submit Icons](#submit-icons)

## How to use

We keep all our icons/images in a `icon` directory, where they are further split up into categories.

The easiest way to use the icons is to use JSDelivr for it.  
Simply use https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/ followed by the name of the foloder (Category), the name of the icon and the file-extension of it.

This link can then be used through Markdown's image-link format (`![text](:link)`) or through the reference link-syntax (`[text]: :link`) to then use in multiple places with `![text]`

### Specific versions

Thanks to releases can you also use specific versions for your icons.  
This is useful if your icon got changed or even removed but you still want to use it.

To use specific versions, replace `main` in `Readme-Icons@v1.0.0` with the version you would like to use (i.e. `Readme-Icons@v1.0.0`).  
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
   If we do plan to remove an icon will we inform you about this through our Pull Request or on our [Discord Server][discord].

## Icons

Here is a complete list of all categories and their available icons.  
The source and respective license(s) will be linked.

**Note:**  
You can right-click a SVG name (In the `Name` collumn) and select "Copy link" to copy the link to the SVG icon.

### Octicons

> **Sources:**
>
> -   https://octicons-primer.vercel.app/octicons/
>
> **License:** [MIT][licenseocticons]
>
> **Base-URL:** https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/

Octicons are GitHubs own SVG icons used across their website but also in various software.  
The default icons are white and have been recolored based on GitHub's colour scheme used.

All icons used are the 16px variant available, which fit perfectly in normal text.

#### Issues

| Name                                           |          Preview          | Notes                                            |
| ---------------------------------------------- | :-----------------------: | ------------------------------------------------ |
| [`IssueClosed.svg`][octiconsissueclosed]       |  ![OcticonsIssueClosed]   | The new icon for closed issues (Not used yet).   |
| [`IssueClosedOld.svg`][octiconsissueclosedold] | ![OcticonsIssueClosedOld] |                                                  |
| [`IssueDrafted.svg`][octiconsissuedrafted]     |  ![OcticonsIssueDrafted]  | The new icon for drafted issues (Not used yet).  |
| [`IssueOpened.svg`][octiconsissueopened]       |  ![OcticonsIssueOpened]   | The new icon for opened issues (Not used yet).   |
| [`IssueOpenedOld.svg`][octiconsissueopenedold] | ![OcticonsIssueOpenedOld] |                                                  |
| [`IssueReopened.svg`][octiconsissuereopened]   | ![OcticonsIssueReopened]  | The new icon for reopened issues (Not used yet). |

[octiconsissueclosed]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueClosed.svg
[octiconsissueclosedold]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueClosedOld.svg
[octiconsissuedrafted]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueDrafted.svg
[octiconsissueopened]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueOpened.svg
[octiconsissueopenedold]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueOpenedOld.svg
[octiconsissuereopened]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/IssueReopened.svg

#### Pull requests

| Name                                                   |            Preview            | Notes                                                  |
| ------------------------------------------------------ | :---------------------------: | ------------------------------------------------------ |
| [`ApprovedChanges.svg`][octiconsapprovedchanges]       |  ![OcticonsApprovedChanges]   |                                                        |
| [`PullRequestClosed.svg`][octiconspullrequestclosed]   | ![OcticonsPullRequestClosed]  | The new icon for closed Pull requests (Not used yet).  |
| [`PullRequestDrafted.svg`][octiconspullrequestdrafted] | ![OcticonsPullRequestDrafted] | The new icon for drafted Pull requests (Not used yet). |
| [`PullRequestMerged.svg`][octiconspullrequestmerged]   | ![OcticonsPullRequestMerged]  |                                                        |
| [`PullRequestOpened.svg`][octiconspullrequestopened]   | ![OcticonsPullRequestOpened]  |                                                        |
| [`RequestedChanges.svg`][octiconsrequestedchanges]     |  ![OcticonsRequestedChanges]  |                                                        |

[octiconsapprovedchanges]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/ApprovedChanges.svg
[octiconspullrequestclosed]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/PullRequestClosed.svg
[octiconspullrequestdrafted]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/PullRequestDrafted.svg
[octiconspullrequestmerged]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/PullRequestMerged.svg
[octiconspullrequestopened]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/PullRequestOpened.svg
[octiconsrequestedchanges]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/RequestedChanges.svg

#### Miscelanious

| Name                                                 |           Preview            | Notes |
| ---------------------------------------------------- | :--------------------------: | ----- |
| [`Comment.svg`][octiconscomment]                     |      ![OcticonsComment]      |       |
| [`ForkedRepository.svg`][octiconsforkedrepository]   | ![OcticonsForkedRepository]  |       |
| [`Release.svg`][octiconsrelease]                     |      ![OcticonsRelease]      |       |
| [`Repository.svg`][octiconsrepository]               |    ![OcticonsRepository]     |       |
| [`StarredRepository.svg`][octiconsstarredrepository] | ![OcticonsStarredRepository] |       |
| [`UnwatchRepository.svg`][octiconsunwatchrepository] | ![OcticonsUnwatchRepository] |       |
| [`WatchRepository.svg`][octiconswatchrepository]     |  ![OcticonsWatchRepository]  |       |
| [`Wiki.svg`][octiconswiki]                           |       ![OcticonsWiki]        |       |

[octiconscomment]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/Comment.svg
[octiconsforkedrepository]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/ForkedRepository.svg
[octiconsrelease]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/Release.svg
[octiconsrepository]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/Repository.svg
[octiconsstarredrepository]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/StarredRepository.svg
[octiconsunwatchrepository]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/UnwatchRepository.svg
[octiconswatchrepository]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/WatchRepository.svg
[octiconswiki]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/octicons/Wiki.svg

### Gifs

> **Sources:**
>
> -   Wave.gif: https://github.com/MartinHeinz/MartinHeinz/
>
> **License:** _Unknown_ (Probably [MIT][licensetwemoji] from Twemoji.)
>
> **Base-URL:** https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/wave

Simple 16x16 pixel gifs you can use for some animation in your Readme.

| Name                   |   Preview   | Notes |
| ---------------------- | :---------: | ----- |
| [`Wave.gif`][gifswave] | ![GifsWave] |       |

[gifswave]: https://cdn.jsdelivr.net/gh/Readme-Workflows/Readme-Icons@v1.0.0/icons/gifs/wave.gif

## Submit Icons

Do you want to add some icons to this Repository?  
If yes, make sure to follow the basic guidelines in our [Contributing file][contributing].
