[中文](README.md) | [English](README.en.md)

# CSRP Builds & Addons Repository

This repository is used to **store and distribute** CSRP build artifacts and community-made addons.  
**It does not contain CSRP source code.** All downloadable files are published under [Releases](../../releases) and managed solely by the repository maintainer.

## Download Acceleration

If Releases downloads are slow, use this GitHub proxy:

https://www.moretools.app/zh-CN/github-proxy

Paste the Release file link into the page to get an accelerated download address. This is a third-party proxy; verify availability and safety at your own discretion.

## Installation

1. Prepare the environment matching the **loader** (NeoForge / Forge / Fabric, etc.) and **game version** indicated by the file.
2. Put the main build `.jar` into the game's `mods/` folder.
3. Put addon JARs into `mods/` as well, and make sure they are compatible with your CSRP version and loader.
4. Launch the game.

> Loader and game version may vary. Always follow the labels in the filename or the Release notes.  
> Addons are created by third-party authors. For compatibility issues, please contact the respective author first.

## Repository Purpose and Storage Policy

This repository only handles distribution and indexing; binaries are not stored on `main`:

- `main` branch: documentation and indexes
- **Releases**: main build JAR, addon JARs
- Binary files such as JAR/ZIP should **not** be committed directly to `main`

## Copyright and License

This repository does not contain CSRP source code; CSRP is copyrighted by its original author.  
Third-party addons remain the property of their respective authors. This repository only indexes and distributes them.

## Acknowledgements

Thanks to the CSRP author, and to everyone who creates, tests, and reports issues for community addons.
