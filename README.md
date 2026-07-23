# WhittyArcade Releases

This public repository hosts official Windows and Linux binaries, release
notes, support issues and the WhittyArcade user guide:

https://crownparkcomputing.github.io/WhittyArcade-Releases/

The emulator implementation is maintained in a separate private repository.
No emulator source code, game ROMs, firmware or keys are published here. The
small HTML/CSS documentation site in this repository is not the emulator
source.

## Download

Use the [v0.2.0 Preview 2 desktop release](https://github.com/CrownParkComputing/WhittyArcade-Releases/releases/tag/v0.2.0-preview.2).

| Platform | Official x86-64 package |
| --- | --- |
| Windows 10 / 11 | `WhittyArcade-windows-x86_64.zip` |
| Ubuntu 24.04 | `WhittyArcade-ubuntu-24.04-x86_64.tar.gz` |
| Debian 13 | `WhittyArcade-debian-13-x86_64.tar.gz` |
| Fedora 43 | `WhittyArcade-fedora-43-x86_64.tar.gz` |
| openSUSE Tumbleweed | `WhittyArcade-opensuse-tumbleweed-x86_64.tar.gz` |
| CachyOS / Arch | `WhittyArcade-cachyos-x86_64.tar.gz` |

Every package includes:

- the native WhittyArcade executable and platform instructions;
- SHA-256 verification data;
- the proprietary binary licence; and
- third-party copyright and licence notices.

The Windows ZIP is portable and includes its required runtime DLLs. Linux
archives are dynamically linked and should be matched to the named
distribution. The separate `.sha256` asset verifies each complete download.

## Current development catalog

WhittyArcade currently recognises 26 working sets across 11 board/runtime
groups. The focused catalog includes Namco System 22 / Super System 22,
System 246, Sega Model 1 and Model 2, Namco System 1, Galaga, Galaxian,
Phoenix, Sega System 16B, Ghosts'n Goblins hardware and an isolated offline
Xbox 360 runtime. Ridge Racer Full Scale is recognised separately and remains
marked not working.

The launcher reads compatible MAME ZIPs and extracted sets directly from its
ROM folder, and disc images from its CHD folder. There is no ROM import,
copy, extraction or repacking step. See the
[public guide](https://crownparkcomputing.github.io/WhittyArcade-Releases/#roms)
for paths, supported short names and the ROM audit.

The public guide also includes a factual
[comparison with FinalBurn Neo](https://crownparkcomputing.github.io/WhittyArcade-Releases/#compare).
The projects have different goals: WhittyArcade focuses on a small set of
cabinet-specific integrations, while FBNeo provides much broader multi-system
coverage and a large Libretro/RetroArch feature ecosystem.

## ROM policy

WhittyArcade does not include or provide game ROMs, firmware, keys or links to
copyrighted game downloads. Users must provide compatible archives that they
are legally entitled to use.

## Support

Use [Issues](https://github.com/CrownParkComputing/WhittyArcade-Releases/issues)
for problems with an official release. Include your Windows version or Linux
distribution, GPU/driver, release version, exact error text and whether the
ROM audit marks the set ready. Do not upload or link to ROM files.

## Download count

The Pages header displays the total number of Windows ZIP and Linux tarball
downloads reported anonymously by GitHub. It excludes checksum clicks. This
repository does not add cookies or custom visitor tracking and does not record
the identity of downloaders.

## Licence

Copyright © 2026 Jonathan Whittingham / CrownParkComputing. All rights
reserved. See [LICENSE](LICENSE) and
[THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).
