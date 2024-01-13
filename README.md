Convert WebAssembly Core Specification to w3m-friendly format
=============================================================

This repository contains a soupault config and supporting files to convert the
WebAssembly Core Specification to a format that is human-readable when browsed
with w3m/lynx. It takes all the MathJax and processes it into plain HTML.

You will need:

- [Soupault](https://soupault.app/), tested with 4.7.0
- Hevea, from the archlinux repos

Then simply clone this repo, including submodules, cd to it and run soupault:

    git clone --recurse-submodules ...
    cd newly-cloned-repo
    soupault

The resulting files will be output in `souped/`.
