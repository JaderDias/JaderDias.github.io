[![GH Pages](https://github.com/JaderDias/jaderdias.github.io/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/JaderDias/jaderdias.github.io/actions/workflows/pages/pages-build-deployment)
# Jader Dias projects site

This project uses Hugo to generate the docs folder, published at https://jaderdias.github.io/

## Prerequisites

1. [Hugo](https://gohugo.io/)

## Building steps

If it's the first time building it since you cloned the repository, you need to download the theme submodule

```
git submodule update --init themes/ananke
```

Then you can rebuild the docs folder for every content modification

```
hugo -D
```

New posts can be created with

```
hugo new posts/my-first-post.md
```

Changes can be previewed with

```
hugo server -D
```
