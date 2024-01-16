# hentaifetch Change Log

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Beta]

## [0.4.2] - 2024-01-16

### Added

-   Fix yoffset and xoffset
    implemented w3m and chafa
-   Fixed default sites
    add nhentai and wholesomelist to default sites
-   Fix the help menu
    be more descriptive about some commands
    add colors to nhentai cookies
-   Add more comments for TODO in the future
    TODO: wrap download function and set timeout (if you're reading this, please PR because idk how to)
    Removed some debug stuff
-   Moved chafa and w3m to their dedicated functions
    Need to talk to chafa dev to add xoffset and yoffset
-   Put everything in wrapped functions nicely (idk if it's more or less readable)
-   Display ID below image (nhentai)

## [0.3.0] - 2023-10-08

### Added

-   Finished image rendering
    add image rendering
-   Implemented neofetch output
    clear terminal when rendering
    calculated numbers such as pixels and aspect ratio

## [0.2.2] - 2023-09-27

### Added

-   Cleaned up a few things
    lewd -> questionable
-   Add loading text
    remove debug logs
-   Support for e-hentai, imgchest, and hmarket.io
    add ID information

## [0.2.1] - 2023-09-27

Cleaned up a little bit of everything, and completed nhentai support.

### Added

-   Changed help command for cookies
-   Consider invalid ID
-   Get random ID from wholesomelist.com
-   Render image in neofetch

## [Unreleased]

## [0.1.2] - 2023-09-15

Finished Danbooru and nhentai support.

### Added

-   Danbooru support.
    Limit the tags to one
-   nhentai support.
    Use wholesomelist.com backend, else use cookies
-   Return "No results found." if no results are found.
    Added jq dependency
-   Reformat code using shfmt
    Use shell-format and ShellCheck extensions

## [0.1.1] - 2023-09-10

Finished Gelbooru support.

### Added

-   Gelbooru support.
    hentaifetch

## [0.1.0] - 2023-09-09

Finished help menu.

### Added

-   Help menu.
    hentaifetch

## [Unreleased] - 2023-09-09

Initial release.

### Added

-   Everything.
    .gitignore
    CHANGELOG.md
    hentaifetch
    LICENSE
    PKGBUILD
    README.md

