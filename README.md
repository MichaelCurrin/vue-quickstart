# Vue.js Quickstart
> Minimal template for a Vue.js app – based on the Vue CLI quickstart

[![Node CI](https://github.com/MichaelCurrin/vue-js-quickstart/workflows/Node%20CI/badge.svg)](https://github.com/MichaelCurrin/vue-js-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-js-quickstart)](https://github.com/MichaelCurrin/vue-js-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=10.X-blue?logo=javascript)](https://nodejs.org)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-js-quickstart/vue)](https://www.npmjs.com/package/vue)


<div align="center">
  
[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vue-js-quickstart/generate)

</div>

<!--
[![View site GH Pages](https://img.shields.io/badge/Demo_site-GH_Pages-green?style=for-the-badge)](https://michaelcurrin.github.io/vue-js-quickstart/)
-->


## About

### What is Vue?

Vue is a JavaScript framework for building web interfaces. If you've heard of React - Vue is similar to React, but Vue is newer, more popular (in GH stars) and easier to learn.

This project provides a quickstart Vue app, which doesn't do much but sets up the skeleton so you can create a Vue app. See for example the minimal [src/App.vue](/src/App.vue) script which includes an HTML template, JavaScript code and CSS code.

### How to use this project

Here is what you can do with this project:

<!--
- See the live demo served on GitHub Pages to see the site in action.
-->

- Click the _Use this Template_ button to add the project to your own repos, then run it locally and on GitHub pages.
- Follow the [Create a fresh quickstart](#create-a-fresh-quickstart) section to create a new Vue app locally, using the Vue CLI.

### Resources

Learn more about [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue) in my Learn to Code project.

- [Vue](https://vuejs.org) homepage
- Vue CLI
    - [CLI](https://cli.vuejs.org/) homepage
    - Creating a Project doc page
        - [Create app](https://cli.vuejs.org/guide/creating-a-project.html#vue-create) command
            ```sh
            $ vue create hello-world
            ```
        - [Using the GUI](https://cli.vuejs.org/guide/creating-a-project.html#using-the-gui) command
            ```sh
            $ vue ui
            ```
- Vue Router
    - [Homepage](https://router.vuejs.org)
    - [Getting Started](https://router.vuejs.org/guide/)


## Requirements

- [Node.js](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md)
- [Yarn](https://classic.yarnpkg.com/en/)


## Installation

### Install system dependencies

Install Node.js and Yarn - see these [gist instructions](https://gist.github.com/MichaelCurrin/bdc34c554fa3023ee81449eb77375fcb).

### Clone repo

Clone this repo, or your own project created from the template.

```sh
$ git@github.com:MichaelCurrin/vue-js-quickstart.git
```

### Install project dependencies

From the project root, run:

```sh
$ yarn install
```

### Recommended extensions

You can install an extension for VS Code for syntax highlighting of `.vue` files.


## Usage
> How to run the Vue app locally

### Run

Compile and hot-reload for development.

```sh
$ yarn serve
```

### Build

Compile and minify for production.

```sh
$ yarn build
```

### Lint and fix

```sh
$ yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy

A Vue app needs a _build_ step to compile the scripts to plain JavaScript. This can be served then as static assets, without a Node.js server.

This repo includes a Github workflow to **test** the app - see the [build_app.yml]/.github/workflows/build_app.yml) workflow file.

This does a production build of the app, but it does **not** persist the built site for serving. But, that can be done by extending the workflow. Or, use Netlify or similar tools to deploy and serve.


## Create a fresh quickstart

How use Vue's builtin quickstart CLI to create a new project. This flow was used originally as the base of this repo.

Ensure you have NodeJS and optionally Yarn installed first.

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

Released under [UNLICENSE](/LICENSE).
