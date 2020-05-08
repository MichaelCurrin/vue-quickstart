# Vue.js Quickstart

[![CI](https://github.com/MichaelCurrin/vue-js-quickstart/workflows/CI/badge.svg)](https://github.com/MichaelCurrin/vue-js-quickstart/actions)
[![Made with Node](https://img.shields.io/badge/Node->=10.X-blue.svg)](https://nodejs.org)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-js-quickstart/vue)](https://www.npmjs.com/package/vue)


## Resources

Learn more about [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue).


## About

This base on the quick start app created like this:


1. Install [Vue CLI](https://cli.vuejs.org/)
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

### System dependencies

1. Install [NodeJS](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/node.md).
2. Install Yarn globally.
    ```sh
    npm install -g yarn
    ```
    
### Project dependencies

```sh
yarn install
```

### Other

Recommended: Install an extension for VS Code for syntax highlighting of `.vue` files.



## Usage
> Run locally


### Compiles and hot-reloads for development

```sh
yarn serve
```

### Compiles and minifies for production

```sh
yarn build
```

### Lints and fixes files

```sh
yarn lint
```

### Customize configuration

See [Configuration Reference](https://cli.vuejs.org/config/).


## Deploy

This repo includes a Github workflow. This does a production deploy of the app but it does not persist the built site - this can be done by extending the workflow. Or use Netlify or similar to deploy and serve.
