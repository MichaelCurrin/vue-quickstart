# Vue.js Quickstart
> Minimal template for a Vue.js app - based on the Vue quickstart

[![CI](https://github.com/MichaelCurrin/vue-js-quickstart/workflows/CI/badge.svg)](https://github.com/MichaelCurrin/vue-js-quickstart/actions)
[![Made with Node](https://img.shields.io/badge/Node.js->=10.X-blue)](https://nodejs.org)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-js-quickstart/vue)](https://www.npmjs.com/package/vue)


## Resources

- Learn more about [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue) in my Learn to Code project.
- [vuejs.org](https://vuejs.org) homepage.
- [vue create](https://cli.vuejs.org/guide/creating-a-project.html#vue-create) command in the docs.
- [vue ui](https://cli.vuejs.org/guide/creating-a-project.html#using-the-gui) command in the commands.


## Requirements

- [Node.js](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md)
- [Yarn](https://classic.yarnpkg.com/en/)


## Installation

### Install system dependencies

Install Node.js and Yarn - see these [gist instructions](https://gist.github.com/MichaelCurrin/bdc34c554fa3023ee81449eb77375fcb).

### Clone

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

This repo includes a Github workflow to test the app - see the [worksflows](/.github/workflows/) directory.

This does a production build of the app but it does not persist the built site - this can be done by extending the workflow. Or use Netlify or similar to deploy and serve.


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

Released under [MIT](/LICENSE).
