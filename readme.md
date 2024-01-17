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

To deploy a new version run:

```sh
mike deploy --push --update-aliases 0.1 latest
mike set-default --push latest
```
