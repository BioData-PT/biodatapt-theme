# BioData.pt Theme for Drupal

[![Deploy](https://github.com/BioData-PT/biodatapt-theme/actions/workflows/ssh-deploy.yml/badge.svg)](https://github.com/BioData-PT/biodatapt-theme/actions/workflows/ssh-deploy.yml)

Maintainer: [Gil Poiares-Oliveira](mailto:gpo@biodata.pt) (INESC-ID | BioData.pt | ELIXIR Portugal)

All BioData.pt logos and imagery are © Associação BIP4DAB - all rights reserved.

Code is available under a [GPL 2.0 license](LICENSE.txt).

Based on [Vartheme BS5](https://www.drupal.org/project/vartheme_bs5). Refer to the [Varbase documentation](https://docs.varbase.vardot.com/v/10.0.x/developers/theme-development-with-varbase)
for more information on development.

## Development

### Install
```sh
yarn install
yarn theme:init
```

### Watch
```sh
yarn theme:watch
```

### Build
```sh
yarn theme:full-build
```

## Deployment

Commits to the `main` branch are [automatically deployed to production web server](https://github.com/BioData-PT/biodatapt-theme/actions/workflows/ssh-deploy.yml) using [GitHub Actions](https://github.com/features/actions).
