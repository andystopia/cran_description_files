# R DESCRIPTION corpus 

This Github contains every R DESCRIPTION file in the ARCHIVE as of 2025-03-06.

A system which makes this consistent and complete with the CRAN is desired, but
I have not implemented it yet.

## Why would I want this?

 - You want a large corpus of CRAN DESCRIPTION files to test a parser / linter with
 - Ecosystem analysis.
  - clustering of packages based on similarity / topic would be super interesting.
 - build tools / package managers
 - you want an up to date corpus. This repository contains
 - write a fast version solver for R by maintaining your own package version index.

```bash
fd DESCRIPTIONS | wc -l
```
 > 155441

files to date. That's a lot to download / scrape, and instead it's possible to just
build off of this.

## Enjoy :) 
