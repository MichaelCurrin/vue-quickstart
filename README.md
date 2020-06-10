# Vue.js Quickstart
> Minimal template for a Vue.js app - based on the Vue quickstart

[![CI](https://github.com/MichaelCurrin/vue-js-quickstart/workflows/CI/badge.svg)](https://github.com/MichaelCurrin/vue-js-quickstart/actions)
[![Made with Node](https://img.shields.io/badge/Node.js->=10.X-blue)](https://nodejs.org)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-js-quickstart/vue)](https://www.npmjs.com/package/vue)


## Resources

Learn more about [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue).


## Create a Vue quickstart

How use Vue's builtin quickstart, which was used to start this project.

1. Install [Vue CLI](https://cli.vuejs.org/).
    ```sh
    npm install -g @vue/cli
    # OR
    yarn global add @vue/cli
    ```
2. Create base. You'll be asked a few questions, like choose between NPM or Yarn approach.
    ```sh
    vue create my-project
    # OR
    vue ui
    ```


## Installation

### Install system dependencies

1. Install [NodeJS](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md).
2. Install Yarn globally.
    ```sh
    npm install -g yarn
    ```
    
### Install project dependencies

```sh
yarn install
```

### Recommended extensions

Install an extension for VS Code for syntax highlighting of `.vue` files.


## Usage
> How to run locally

### Run

Compile and hot-reload for development

```sh
yarn serve
```

### Build

Compile and minift for production

```sh
yarn build
```

### Lint and fix

```sh
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy

This repo includes a Github workflow to test the app - see the [worksflows](/.github/workflows/) directory.

This does a production build of the app but it does not persist the built site - this can be done by extending the workflow. Or use Netlify or similar to deploy and serve.


## License

Released under [MIT](/LICENSE).
