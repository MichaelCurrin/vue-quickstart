# Vue.js Quickstart
> Minimal Vue app template which uses CI to deploy to GitHub Pages

[![GH Pages Deploy](https://github.com/MichaelCurrin/vue-quickstart/workflows/GH%20Pages%20Deploy/badge.svg)](https://github.com/MichaelCurrin/vue-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-quickstart)](https://github.com/MichaelCurrin/vue-js-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=10.X-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->=1.X-blue?logo=yarn&logoColor=white)](https://classic.yarnpkg.com)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-quickstart/vue?logo=vue.js)](https://www.npmjs.com/package/vue)


## Preview

<div align="center">
    <a href="https://michaelcurrin.github.io/vue-quickstart/">
        <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="600" />
    </a>
</div>


## Use this project

<div align="center">

[![View site GH Pages](https://img.shields.io/badge/Demo_site-GH_Pages-green?style=for-the-badge)](https://michaelcurrin.github.io/vue-quickstart/)
[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vue-quickstart/generate)

</div>


## About

### What is Vue?

Vue is a JavaScript framework for building web interfaces. If you've heard of React - Vue is similar to React, but Vue is newer, more popular (in GH stars) and easier to learn.

This project provides a quickstart Vue app, which doesn't do much but sets up the skeleton so you can create a Vue app. See for example the minimal [src/App.vue](/src/App.vue) script which includes an HTML template, JavaScript code and CSS code.

See the links at the top - view the live demo and then create your own repo from the template.

Or follow the [Create a fresh quickstart](#create-a-fresh-quickstart) section to create a new Vue app from scratch, using the Vue CLI.

If you are looking for a multi-page Vue app template, see this repo - [MichaelCurrin/vue-router-quickstart](https://github.com/MichaelCurrin/vue-router-quickstart).


### Resources

Learn more about [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue) in my Learn to Code project.

- [Vue](https://vuejs.org) homepage
- Vue CLI
    - [CLI](https://cli.vuejs.org/) homepage
    - [Creating a Project](https://cli.vuejs.org/guide/creating-a-project.html) doc page, for if you want to start a fresh project.
        - [Create app](https://cli.vuejs.org/guide/creating-a-project.html#vue-create) command
            ```sh
            $ vue create hello-world
            ```
        - [Using the GUI](https://cli.vuejs.org/guide/creating-a-project.html#using-the-gui) command
            ```sh
            $ vue ui
            ```
    - [Plugins and presets](https://cli.vuejs.org/guide/plugins-and-presets.html)
        - e.g.
            ```sh
            $ vue add eslint
            $ vue add router
            $ vue add vuetify
            ```
- Vue Router
    - [Homepage](https://router.vuejs.org)
    - [Getting Started](https://router.vuejs.org/guide/)
    - [HTML5 History mode](https://router.vuejs.org/guide/essentials/history-mode.html)
- Vuetify
    - [Homepage](https://vuetifyjs.com/)
        > Material Design Component Framework
        >
        > Vuetify is a Vue UI Library with beautifully handcrafted Material Components. No design skills required — everything you need to create amazing applications is at your fingertips.


## Requirements

- [Node.js](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md)
- [Yarn](https://classic.yarnpkg.com/en/)


## Installation
> How to setup the app locally

### Install system dependencies

Install Node.js and Yarn - see these [gist instructions](https://gist.github.com/MichaelCurrin/bdc34c554fa3023ee81449eb77375fcb).

### Clone

Clone the repo - or your own repo generated from the template

```sh
$ git clone git@github.com:MichaelCurrin/vue-quickstart.git
$ cd vue-quickstart
```

### Install project dependencies

Install Node.js packages.

```sh
$ yarn install
```

### Recommended extensions

To add syntax highlighting of `.vue` files in VS Code, install an extension such as [Vetur](https://marketplace.visualstudio.com/items?itemName=octref.vetur).


## Usage
> How to run the app locally

### Run

Compile and start a hot-reloading dev server.

```sh
$ yarn serve
```

Open in the browser:

- https://localhost:8080

### Build

Compile and minify for production.

```sh
$ yarn build
```

View the output in the unversioned `dist` directory.

### Lint

Detect errors and warnings and fix where possible.

```sh
$ yarn lint:fix
```

Run linter but not fix up. Warnings will pass, but any errors will cause an error exit status - this is useful for a CI/CD flow.

```sh
$ yarn lint:check
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy
> How to build and deploy this app to GitHub Pages

### Run CI/CD with GitHub Actions

This project uses a GitHub Actions flow for CI/CD.

Just push or merge to master the workflow will build and deploy the app to the `gh-pages` branch.

### Setup GH Pages

Set this up to be served on GitHub Pages:

1. Go to repo _Settings_.
2. Go to _GitHub Pages_ section.
3. Enable the site on `gh-pages` branch `root` directory.
4. Wait for your site to build.
5. Check the Actions tab on the repo for the status of the build.
6. Open the public URl when it is done. e.g. https://MichaelCurrin.github.io/vue-quickstart

### Notes

A Vue app needs a _build_ step to compile the scripts to plain JavaScript. This output can then be served then a static asset directory, without a Node.js server running.

This repo includes a GitHub Actions workflow to build and deploy to the `gh-pages` branch on GitHub, so it can be served using GitHub Pages. This is handled in the [main.yml](/.github/workflows/main.yml) workflow file.

Note that in order to serve on a subpath on GH Pages, the project name is set in [vue.config.js](/vue.config.js). See this covered [here](https://cli.vuejs.org/config/#target-browsers) in the Vue docs.

Optional for `.gitignore`, based on the Vue CLI quickstart.

```
.env.local
.env.*.local
```


## Create a fresh quickstart

How use Vue's builtin quickstart CLI to create a new project. This flow was used originally as the base of this repo.

Ensure you have Node.js and optionally Yarn installed first.

### Use npx

Use this is install and run the vue CLI to create a new project. This will not persist any package in your global packages.

```sh
$ npx @vue/cli create --default my-project
```

### Install and run the CLI


#### Use the create command

Create a base Vue project. This will download vue CLI if not installed.


```sh
$ npx vue create my-project
```

You'll be asked a few questions, like choose between NPM or Yarn approach.

Add the `--default` flag to skip prompts.


#### Add Vue CLI to a project

How to install [Vue CLI](https://cli.vuejs.org/).

This can be installed globally:

- NPM
    ```sh
    $ npm install -g @vue/cli
    ```
- Yarn
    ```sh
    $ yarn global add @vue/cli
    ```

#### Use a GUI

You can also create and manage projects using a graphical interface with the `vue ui` command:

```sh
$ npx vue ui
```

The above command will open a browser window with a GUI that guides you through the project creation process.


## License

Released under [MIT](/LICENSE).
