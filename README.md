# VuePress Quickstart
> Starter template for a VuePress project

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

Get a project like this one.

<div align="center">

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vuepress-quickstart/generate)

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

Build the site to an output directory.

```sh
$ yarn build
```

The output path will be at `docs/src/dist/`.

That output can then be served as static content of for a website.

If you use a CI tool, you can have that build step happen in the cloud on a commit.

For Netlify, you can configure the site the build and target directory.

For GitHub Actions, you can build the site and commit the result to `gh-pages` branch, which can be served with GitHub Pages.


## Create a fresh project

Use the VuePress CLI tool to bootstrap a new project in a local directory. 

Make sure you have Node.js 10+ installed and optionally Yarn installed too.

These commands will work even if you don't have VuePress installed locally.

- Using NPM / NPX:
    ```sh
    $ npx create-vuepress-site my-app
    ```
- Using Yarn:
    ```sh
    $ yarn create vuepress-site my-app
    ```


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
