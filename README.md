# Simpla Components [WIP]

This is a monorepo of all of Simpla's official content components

## A what?

A [monorepo](https://medium.com/@maoberlehner/monorepos-in-the-wild-33c6eb246cb9), a single git repository that contains several packages. Each component (eg: `simpla-text`, `simpla-img`) is a separate NPM package under `components/`.

The monorepo approach makes maintaining large modular projects like Simpla much easier, and is followed by other successful ecosystems like [Babel](https://github.com/babel/babel) and [React](https://github.com/facebook/react).

We use [lerna](https://lernajs.io/) to manage it.

## Components

Each component has its own README, `package.json`, etc in its folder under `components/`.

These are the official components currently managed here:

Component         | Version
----------------- | ----------------------
simpla-text       | ![][simpla-text]
simpla-img        | ![][simpla-img]
simpla-article    | ![][simpla-article]
simpla-video      | ![][simpla-video]
simpla-link       | ![][simpla-link]
simpla-collection | ![][simpla-collection]
simpla-admin      | ![][simpla-admin]

## Issues

Use this format when filing a Github issue for a component:

```
[component-name] Message
```

For example: `[simpla-text] Something is broken`

---

MIT © [Sean King](https://github.com/seaneking) & [Bede Overend](https://github.com/bedeoverend)

<!-- Badges -->
[simpla-text]: 	https://img.shields.io/npm/v/@simplajs/simpla-text.svg
[simpla-img]: 	https://img.shields.io/npm/v/@simplajs/simpla-img.svg
[simpla-article]: 	https://img.shields.io/npm/v/@simplajs/simpla-article.svg
[simpla-collection]: 	https://img.shields.io/npm/v/@simplajs/simpla-collection.svg
[simpla-admin]: 	https://img.shields.io/npm/v/@simplajs/simpla-admin.svg
[simpla-video]: 	https://img.shields.io/npm/v/@simplajs/simpla-video.svg
[simpla-link]: 	https://img.shields.io/npm/v/@simplajs/simpla-link.svg