mod-pkgs
===

An open package repository for Minecraft mods, drawing inspiration from (among others)
[winget-pkgs] for structure, [Maven] for certain metadata, and [Homebrew] for its Cask
system.

## How this would work?

This repository will be where the development of mod packages goes, though tooling should
support multiple package lists.

This repository will be the human-level interaction for packages, though for the sake of
writing tooling would likely be built into another "machine" format (such as JSON).

The data will be open for all to use and consume, launchers, web devs, anyone - developers
are encouraged to built whatever they like on this data. The important thing is user choice,
they may decide which site they browse for searching packs for example, or what CLI they
use to install mods, or what launcher they use.

To draw comparissions to other projects, think of Homebrew's Casks or NPM Registry.

## FAQs

### Discuss

I have tentatively make an IRC channel, #modpkgs, on EsperNet.

### Why XML?

XML is a great language for humans to write with, and with time we'll be able to assign
the manifest files a strong, documented, XML schema.

[winget-pkgs]: https://github.com/microsoft/winget-pkgs
[Maven]: https://maven.apache.org/
[Homebrew]: https://brew.sh/
