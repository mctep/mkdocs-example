# Open Data Manager Documentation

This repo contains documentation site for ODM product.

Documentation site is based on [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/).

## Development

```sh
pip install mkdocs-material
pip install mike
```

To serve documentation on localhost:

```sh
mkdocs serve
```

## Deployment

Deployment latest version is configured via Github Actions.

[Mike](https://squidfunk.github.io/mkdocs-material/setup/setting-up-versioning/#usage) plugin is used for deploying versions.

To deploy a new version create a new branch with pattern `v*.*.*` (for example `v1.54.2`) and push it.

A new folder will be created in `gh-pages` branch that will be available on Github Pages after some time.

## Markdown syntax

The documentation based on [Markdown Syntax](https://www.markdownguide.org/basic-syntax/). Also it supports [Extended Syntax](https://www.markdownguide.org/extended-syntax/).

Also there is a lot of additional markdown features. See the [reference](https://squidfunk.github.io/mkdocs-material/reference/).

If something does not work please feel free to contact with developers.
