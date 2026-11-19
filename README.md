# Parcel Starter Kit

> Simple boilerplate: Parcel 2, Bulma 1, SCSS, PostHTML, ESLint, Stylelint and Prettier

[![CI](https://github.com/emendelski/parcel-starter-kit/actions/workflows/ci.yml/badge.svg)](https://github.com/emendelski/parcel-starter-kit/actions/workflows/ci.yml)

## What's inside

- **[Parcel 2](https://parceljs.org/)**: zero-config bundler. JavaScript is transpiled with SWC and CSS is minified and vendor-prefixed with Lightning CSS, both based on `.browserslistrc`.
- **[Bulma 1](https://bulma.io/)**: CSS framework, imported with Sass modules (`@use`).
- **[Sass](https://sass-lang.com/)**: SCSS stylesheets.
- **[PostHTML Include](https://github.com/posthtml/posthtml-include)**: HTML partials via `<include src="…" />`.
- **[ESLint](https://eslint.org/)**: flat config with the recommended rules.
- **[Stylelint](https://stylelint.io/)**: `stylelint-config-standard-scss`.
- **[Prettier](https://prettier.io/)**: code formatting.

## Requirements

Node.js 22.22+, 24.15+ or 26+ (see `.nvmrc`).

## Usage

```bash
# install dependencies
npm install

# dev server with hot reload at http://localhost:1234
npm run dev

# lint JavaScript and SCSS
npm run lint

# format all files (or check formatting with format:check)
npm run format

# production build to dist/
npm run build
```
