# Contralto

Contralto is a minimal [Ghost](https://github.com/TryGhost/Ghost) theme based on [Alto](https://github.com/TryGhost/Alto) featuring a light and dark mode, and French and English localization enabled.

**Demo: https://alto.ghost.io**

# Installation instructions

1. [Download this theme](https://github.com/gersande/alto-gersande/archive/main.zip)
2. Log into Ghost, and go to the `Design` settings area to upload the zip file

# Development

Styles are compiled using Gulp/PostCSS to polyfill future CSS spec. You'll need [Node](https://nodejs.org/), [Yarn](https://yarnpkg.com/) and [Gulp](https://gulpjs.com) installed globally. After that, from the theme's root directory:

```bash
# Install
yarn

# Run build & watch for changes
yarn dev
```

Now you can edit `/assets/css/` files, which will be compiled to `/assets/built/` automatically.

The `zip` Gulp task packages the theme files into `dist/alto.zip`, which you can then upload to your site.

```bash
yarn zip
```

# Copyright & License

Copyright (c) 2013-2022 Ghost Foundation - Released under the [MIT license](LICENSE).
