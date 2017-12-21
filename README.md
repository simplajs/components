<p align="center">
  <a href="https://www.simplajs.org">
    <img src="https://www.simplajs.org/assets/public/logo.png" alt="Simpla" width="300">
  </a>
</p>

This is a monorepo of all of Simpla's official content components

Component         | Version
----------------- | ----------------------
simpla-text       | ![][simpla-text]
simpla-img        | ![][simpla-img]
simpla-article    | ![][simpla-article]
simpla-video      | ![][simpla-video]
simpla-link       | ![][simpla-link]
simpla-collection | ![][simpla-collection]
simpla-admin      | ![][simpla-admin]

## A what?

A [monorepo](https://medium.com/@maoberlehner/monorepos-in-the-wild-33c6eb246cb9), a single git repository that contains several packages. Each component (eg: `simpla-text`, `simpla-img`) is a separate NPM package under `components/`.

The monorepo approach makes maintaining large modular projects like Simpla much easier, and is followed by other successful ecosystems like [Babel](https://github.com/babel/babel) and [React](https://github.com/facebook/react).

We use [lerna](https://lernajs.io/) to manage it.

## Documentation

All components have their own documentation, demos, and API references in their folder under `components`, which in turn is listed on [webcomponents.org](https://webcomponents.org). You can find them in the [simpla-elements](https://www.webcomponents.org/collection/simplajs/simpla-elements) collection there.

## Issues

Use this format when filing a Github issue for a component:

```
[component-name] Message
```

For example: `[simpla-text] Something is broken`

## Contributing

There are lots of ways you can help push the Simpla project forward:

- **Reporting bugs.** If you find a bug please report it! Open an issue against this repository for problems with any of the components, or the [simplajs/simpla](https://github.com/simplajs/simpla) repo for problems with the core library.

- **Submitting Pull Requests.** We ❤️ PRs! Your PR should address an existing issue or have been discussed previously to ensure it gets merged.

- **Publishing new components** Simpla is a community driven project, and the best way you can contribute is to build your own content components! If you'd like to suggest your component to be added to this official collection, submit a PR for us to review. The ecosystem is built on Web Components, but there's no reason you couldn't use Simpla in a component environment of your choice (React, etc).

Read the [Contributing guidelines](/CONTRIBUTING.md) for more information.

---

[MIT](/LICENSE) © 2017

<!-- Badges -->
[simpla-text]: 	https://img.shields.io/npm/v/@simplajs/simpla-text.svg
[simpla-img]: 	https://img.shields.io/npm/v/@simplajs/simpla-img.svg
[simpla-article]: 	https://img.shields.io/npm/v/@simplajs/simpla-article.svg
[simpla-collection]: 	https://img.shields.io/npm/v/@simplajs/simpla-collection.svg
[simpla-admin]: 	https://img.shields.io/npm/v/@simplajs/simpla-admin.svg
[simpla-video]: 	https://img.shields.io/npm/v/@simplajs/simpla-video.svg
[simpla-link]: 	https://img.shields.io/npm/v/@simplajs/simpla-link.svg
