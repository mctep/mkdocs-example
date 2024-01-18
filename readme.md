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
