# VuePress Quickstart
> Starter template for a VuePress project - including CI for GH Pages hosting

[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vuepress-quickstart?include_prereleases=&sort=semver)](https://github.com/MichaelCurrin/vuepress-quickstart/releases/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->=1-blue?logo=yarn&logoColor=white)](https://classic.yarnpkg.com)

[![dependency - vuepress](https://img.shields.io/badge/dependency-vuepress-blue)](https://www.npmjs.com/package/vuepress)


## Preview

<div align="center">
    <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="500" />
</div>


## Start your VuePress project

Get a project like this one by clicking the button.

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vuepress-quickstart/generate)

</div>

Then follow the [Installation](#installation) and [Usage](#usage) instructions below.


## Why VuePress?

Build a modern, static website using markdown for content. Great for a docs site.

From the homepage:

> Simplicity First - Minimal setup with **markdown-centered** project structure helps you focus on writing.
>
> Vue-Powered - Enjoy the dev experience of Vue + webpack, use Vue components in markdown, and develop custom themes with Vue.
>
> Performant - VuePress generates pre-rendered **static HTML** for each page, and runs as an **SPA** once a page is loaded.

To learn more about VuePress, the [Vuerpress](https://vuepress.vuejs.org/) homepage or my my [Vuepress resources](https://michaelcurrin.github.io/dev-resources/resources/javascript/packages/vuepress/) page.


## Create a fresh project

Here is how to the VuePress CLI tool to bootstrap a new project in a local directory.

[![vuepress - create-vuepress-site](https://img.shields.io/static/v1?label=vuepress&message=create-vuepress-site&color=blue&logo=github)](https://github.com/vuepress/create-vuepress-site)

Make sure you have Node.js 10+ installed and Yarn, if used below.

These commands will work even if you don't have VuePress installed locally.

- Using NPM / NPX:
    ```sh
    $ npx create-vuepress-site my-app
    ```
- Using Yarn:
    ```sh
    $ yarn create vuepress-site my-app
    ```

Then navigate to the app.

```sh
$ cd my-app
$ cd docs
```


## Installation

### Install system dependencies

Install Node.js and Yarn - see [instructions](https://gist.github.com/bdc34c554fa3023ee81449eb77375fcb).

### Clone

Create a new project from this template or the template repo.

Clone the repo.

```sh
$ git clone git@github.com:MichaelCurrin/vuepress-quickstart.git
$ cd vuepress-quickstart
```

### Install project packages

All the content is in [docs](/docs/), so navigate there.

```sh
$ cd docs
```

Install NPM packages with YRN.

```sh
$ yarn install
```

## Usage

```sh
$ cd docs
```

### Server

Start a dev server.

```sh
$ yarn dev
```


## Deploy

### Build

Build the site to an output directory.

```sh
$ yarn build
```

The output path will be at `docs/src/.vuepress/dist/`.

That output can then be served as static content of for a website.

### CI

If you use a CI tool, you can have that build step happen in the cloud on a commit.

For _GitHub Actions_, you can build the site and commit the result to `gh-pages` branch, which can be served with GitHub Pages. See [docs.yml](/.github/workflows/docs.yml) workflow.

1. Commit and push your repo.
2. View the _Actions_ tab to check that that build pages.
3. Go to your repo's Settings and enable GitHub Pages for the `docs` branch.
4. View your site.

This project is setup to serve as a subpath on GitHub Pages, using `base` as per the [Config](https://vuepress.vuejs.org/config/) page of the docs. This is setup in [config.js](/docs/src/.vuepress/config.js).

For a _Netlify_ site, you can configure the site the build command and target directory. See my [Configure](https://michaelcurrin.github.io/code-cookbook/recipes/ci-cd/netlify/configure.html) guide.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
