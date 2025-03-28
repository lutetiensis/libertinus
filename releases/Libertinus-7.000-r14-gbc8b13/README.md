# Libertinus Font Family

[![Latest Release](https://img.shields.io/github/v/release/alerque/libertinus?label=Download%20Release&logo=Github)](https://github.com/alerque/libertinus/releases/latest)
[![All Releases](https://img.shields.io/github/downloads/alerque/libertinus/total)](https://github.com/alerque/libertinus/releases)
[![Fontship Build Status](https://img.shields.io/github/workflow/status/alerque/libertinus/Fontship?label=Fontship&logo=Codeship)](https://github.com/alerque/libertinus/actions?workflow=Fontship)

![Sample of Libertinus Font Family](preview.svg)

The Libertinus family consists of:

* **Libertinus Serif**: forked from *Linux Libertine*.
* **Libertinus Sans**: forked from *Linux Biolinum*.
* **Libertinus Mono**: forked from *Linux Libertine Mono*.
* **Libertinus Math**: an OpenType math font for use in OpenType math-capable applications (such as LuaTeX, XeTeX, or MS Word 2007+).

## Download

Downloads containing all the ready to use font files and documentation can be found on the [Releases][3] page of the project on GitHub.

To preview changes in between tagged releases, the fonts resulting from each change can be downloaded as artifacts attached to each commit under the [Fontship workflow in the Actions tab](https://github.com/alerque/libertinus/actions?query=workflow%3AFontship).

## Building

Font files for this project are generated using [Fontship][fontship].
Several methods are available for installation including a simple one-liner with no installation [using Docker][fontship-docker-setup].
Once equipped with Fontship, to build your own copy of this font project from scratch or to modify the sources and generate your own fonts, simply clone this repository, then run:

```console
$ fontship make
```

*Note*: This repository’s default branch was filtered after the v6.12 release to remove all of the binary OTF and other generated files from the commit history.
If you are cloning this repository just for the sources and don’t wish to download ~300MB worth of every font change ever built, please add `--single-branch` to your Git clone command.

## Contributing

Community contributions are welcome.
See the file [CONTRIBUTING.md](CONTRIBUTING.md) for instructions on how to build the fonts and contribute changes.

## History

The Libertinus font project began as a fork of the [Linux Libertine][1] and Linux Biolinum fonts.
Libertinus was forked from the [5.3.0 (2012-07-02) release][2] of Linux Libertine fonts.
The original impetus was to add an OpenType math companion to the Libertine font family.
Over time it grew into to a full-fledged fork addressing many of the bugs in the Libertine fonts.

Hat-tip to [Frédéric Wang][fred-wang] for coming up with the name “Libertinus”.

Thanks to [Khaled Hosny][khaledhosny] who was the primary contributor and maintainer from 2012–2020.
If you like this font please thank and even consider sponsoring him!

In 2020, Khaled passed the role of maintainer on to [Caleb Maclennan][alerque].

## License

All fonts in the Libertinus family are available under the terms of the Open Font License, version 1.1.
See the file [OFL.txt](OFL.txt) for details.

[1]: https://en.wikipedia.org/wiki/Linux_Libertine
[2]: https://sourceforge.net/projects/linuxlibertine/files/linuxlibertine/
[3]: https://github.com/alerque/libertinus/releases
[khaledhosny]: https://github.com/khaledhosny
[alerque]: https://github.com/alerque
[fred-wang]: https://github.com/fred-wang
[fontship]: https://github.com/theleagueof/fontship
[fontship-docker-setup]: https://github.com/theleagueof/fontship#docker-setup
