# hentaifetch

[Neofetch](https://github.com/dylanaraps/neofetch/) but with hentai

## Installation

Because this is a ~~beta~~ alpha version, there isn't an official installation script yet.
To test it out, git clone the repo, cd into it, and run `./hentaifetch`.
I've tested it out on Arch, but theoretically it should work on any distro.
Just make sure neofetch and jq are installed (see PKGBUILD file and the dependencies field).

## Usage

Running `./hentaifetch` won't do anything _as of right now_, unless you're lucky (a 20% or 3/15 chance) to actually get it working.
Instead, run `./hentaifetch -s` along with one of the three sites: `danbooru`, `gelbooru`, or `nhentai`.
Currently, the `--id`, `--tags`, `-e`, `-l` flags are fully functional. >! (Need reworking for nhentai)
Other sites will be added in the future.
