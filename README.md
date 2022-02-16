Jader Dias projects site
========================

This project uses [hugo](https://gohugo.io/) to generate the docs folder, published at https://jaderdias.github.io/

If it's the first time building it since you cloned the repository, you need to download the theme submodule

```
git submodule update themes/ananke
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
