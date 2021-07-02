[semver]: https://semver.org/
[icons]: https://github.com/Readme-Workflows/Readme-Icons/tree/main/icons

# Readme Icons Version Policy
We use releases to allow you to use a specific instance of an icon in case it was changed or even removed.

The Releases of this repository follow basic [Semantic Versioning][semver] with a few specific changes regarding what part of a version is receiving an update.  
The version format is the basic semantic version format (`vMAJOR.MINOR.PATCH`) and follows the following Update-rules:

### Major
The `Major` version is updated in the following events:

- New Set of Icons (New Category) added to the [`icons`][icons] folder.
- Existing Icon Set removed from the [`icons`][icons] folder.
- Existing Icon Set renamed.

### Minor
The `Minor` version is updated in the following events:

- Existing Icon was replaced/updated. Does not include Colour changes (See [`Patch`](#patch)
- Existing Icon was removed.
- Existing Icon was renamed.

### Patch
`Patch` is updated in the following cases:

- Colours of an Icon change
- New Icons are added to an **existing** Icon Set.
- Any other case not covered by [`Major`](#major) or [`Minor`](#minor) that doesn't affect the URL to a Icon or Icon Set.
