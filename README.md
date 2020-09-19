# Vue.js Quickstart
> Minimal Vue app template which uses CI to deploy to GitHub Pages

[![GH Pages Deploy](https://github.com/MichaelCurrin/vue-quickstart/workflows/GH%20Pages%20Deploy/badge.svg)](https://github.com/MichaelCurrin/vue-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-quickstart)](https://github.com/MichaelCurrin/vue-js-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=10.X-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->=v1-blue?logo=yarn&logoColor=white)](https://classic.yarnpkg.com)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-quickstart/vue?logo=vue.js)](https://www.npmjs.com/package/vue)


## Preview

<div align="center">
    <a href="https://github.com/MichaelCurrin/vue-quickstart/generate">
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

Install Node packages.

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

### Lint and fix

```sh
$ yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy

A Vue app needs a _build_ step to compile the scripts to plain JavaScript. This output can then be served then a static asset directory, without a Node.js server running.

This repo includes a GitHub workflow to build the app - see the [build_app.yml]/.github/workflows/build_app.yml) workflow file.

This does a production build of the app, but it does **not** persist the built site for serving on GitHub Pages. That can be done easily by extending the workflow. See this [workflow](https://github.com/MichaelCurrin/react-create-app-quickstart/blob/master/.github/workflows/main.yml) which deploys a React app. Or use Netlify instead.


## Create a fresh quickstart

How use Vue's builtin quickstart CLI to create a new project. This flow was used originally as the base of this repo.

Ensure you have Node.js and optionally Yarn installed first.

### Use npx

Use this is install and run the vue CLI to create a new project. This will not persist any package in your global packages.

```sh
$ npx @vue/cli create --default my-project
```

### Install and run the CLI

#### Install the CLI

Install [Vue CLI](https://cli.vuejs.org/).

This can be installed globally:

```sh
$ npm install -g @vue/cli
$ # OR
$ yarn global add @vue/cli
```

#### Use the create command

Create the base. You'll be asked a few questions, like choose between NPM or Yarn approach.

```sh
$ vue create my-project
```

Add the `--default` flag to skip prompts.

#### Use a GUI

You can also create and manage projects using a graphical interface with the vue ui command:

```sh
$ vue ui
```

The above command will open a browser window with a GUI that guides you through the project creation process.


## License

Released under [MIT](/LICENSE).
