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
fd DESCRIPTION | wc -l
```
 > 177831

files to date. That's a lot to download / scrape, and instead it's possible to just
build off of this.

## Format

Each folder has a subfolder of versions of R packages, each folder contains a description file.

You might think this strange. Sure. The idea is that it's easy to walk and generate
a new file derived from the old file, in a way that's seperable. Regardless,
with a little Python, R, or Bash and some scripting, I imagine it's not terribly difficult to reshape.

## Security Warning.

R DESCRIPTION files contain R code. Certain loaders may execute that R code.

## Will I accept PR's which include more DESCRIPTION files?

yes.

## Enjoy :) 
