# VuePress Quickstart
> Starter template for a VuePress project

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vuepress-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/vuepress-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->=1-blue?logo=yarn&logoColor=white)](https://classic.yarnpkg.com)
[![dependency - vuepress](https://img.shields.io/badge/dependency-vuepress-blue)](https://www.npmjs.com/package/vuepress)


<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vuepress-quickstart/generate)

</div>


## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" />
</div>


## Why VuePress?

Build a modern, static website using markdown for content. Great for a docs site.

From the homepage:

> Simplicity First - Minimal setup with **markdown-centered** project structure helps you focus on writing.
>
> Vue-Powered - Enjoy the dev experience of Vue + webpack, use Vue components in markdown, and develop custom themes with Vue.
>
> Performant - VuePress generates pre-rendered **static HTML** for each page, and runs as an **SPA** once a page is loaded.

To learn more about VuePress, see my [Resources](https://michaelcurrin.github.io/dev-resources/resources/javascript/packages/vuepress/) page.


## How to use this project

Install Node.js and Yarn - see [instructions](https://gist.github.com/bdc34c554fa3023ee81449eb77375fcb).

Create a new project from this template.

Clone it.

```sh
$ git clone git@github.com:MichaelCurrin/vuepress-quickstart.git
$ cd vuepress-quickstart
```

All the content is in `docs`, so navigate there.

```sh
$ cd docs
```

Install project packages.

```sh
$ yarn install
```

Start a dev server.

```sh
$ yarn dev
```

Build the site to an output directory. This can be served as static assets.

```sh
$ yarn build
```

The output will be at `docs/src/dist/`.


## Create a fresh project

Use VuePress' CLI tool to bootstrap a new project in a local directory. 

Make sure you have Node.js 10+ installed and optionally Yarn installed too.

You can use the create commands without having to install any packages globally.

- Using NPM / NPX
    ```sh
    $ npx create-vuepress-site my-app
    ```
- Using Yarn
    ```sh
    $ yarn create vuepress-site my-app
    ```


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
