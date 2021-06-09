# Vue Quickstart
> Starter template for a Vue 3 site - including docs and CI deploy to GH Pages

<!-- Badges generated with: https://michaelcurrin.github.io/badge-generator/ -->
[![Deploy GH Pages](https://github.com/MichaelCurrin/vue-quickstart/workflows/Deploy%20GH%20Pages/badge.svg)](https://github.com/MichaelCurrin/vue-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-quickstart)](https://github.com/MichaelCurrin/vue-js-quickstart/tags/)
[![License](https://img.shields.io/badge/License-MIT-blue)](#license)

[![Made with Node](https://img.shields.io/badge/Node.js->=12-blue?logo=node.js&logoColor=white)](https://nodejs.org)
[![Made with Yarn](https://img.shields.io/badge/Yarn->=1-blue?logo=yarn&logoColor=white)](https://classic.yarnpkg.com)
[![Made with Vue](https://img.shields.io/github/package-json/dependency-version/MichaelCurrin/vue-quickstart/vue?logo=vue.js)](https://www.npmjs.com/package/vue)


## Preview

<div align="center">
    <a href="https://michaelcurrin.github.io/vue-quickstart/">
        <img src="/sample.png" alt="Sample screenshot" title="Sample screenshot" width="600" />
    </a>
</div>


## Use this project

<div align="center">

[![View site GH Pages](https://img.shields.io/badge/View-Demo_site-blue?style=for-the-badge)](https://michaelcurrin.github.io/vue-quickstart/)

[![Use this template](https://img.shields.io/badge/Generate-Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vue-quickstart/generate)

</div>

After you've looked at the demo screenshot and site, you are welcome to create your own using the template button. This will copy this project and add it to your repos (no forking needed, but please star the original repo).


## Documentation
> How to install and run the app locally and deploy it to GH Pages

<div align="center">

[![View - Documentation](https://img.shields.io/badge/View-Documentation-blue?style=for-the-badge)](/docs/)

</div>


## About

### What is Vue?

> Vue.js is a progressive, incrementally-adoptable JavaScript framework for building UI on the web.

### Why not React?

Vue is intended to be more beginner-friendly (I agree it is) and the [vue](https://github.com/vuejs/vue) repo has more GH stars than the [react](https://github.com/facebook/react) repo, if that is any indication of adoption by the community.

Vue is open-source and was created by one person originally. React was created at Facebook.

### Resources

Need are some resources to get started or learn more advanced topics?

See [Vue](https://github.com/MichaelCurrin/learn-to-code/blob/master/en/topics/scripting_languages/JavaScript/frameworks.md#vue) in my Learn to Code project.

### Origin

This project was created using the Vue CLI:

```sh
$ vue create my-project
$ # OR if not installed.
$ npx @vue/cli create my-project
```

See the [Creating a project](https://cli.vuejs.org/guide/creating-a-project.html) section of the docs.

This project used mostly default content from that command, but adds the following:

- Sample image
- Detailed docs
- GH Pages setup
- Linting with and without fixes
- Prettier

On the last point, the `prettier` package was added so that it can be used when linting to pick up inconsistent styling. For example:

```
...
warning: Insert `;` (prettier/prettier) at vue.config.js:5:2:
...
```

See these areas in [package.json](/package.json):

- `eslint-plugin-prettier` package
- `prettier` package
- `@vue/prettier` in ESLint config

That based on what you get in the Vue Router setup.


## Related projects

- Vue-based projects:
    - [Vue TypeScript Quickstart](https://github.com/MichaelCurrin/vue-typescript-quickstart) - like this project but with TypeScript added.
    - [Vue Router Quickstart](https://github.com/MichaelCurrin/vue-router-quickstart) - like this project but with Vue Router added for a multi-page site.
    - [Vue Vuex Quickstart](https://github.com/MichaelCurrin/vue-vuex-quickstart) - like this project but with Vuex added.
    - [VuePress Quickstart](https://github.com/MichaelCurrin/vuepress-quickstart) - using VuePress, a static site generator built on a Vue.
    - [Nuxt Default Quickstart](https://github.com/MichaelCurrin/nuxt-default-quickstart) - using Nuxt, a mix between a SPA and a static site generator that is built on Vue.
    - [Vue Frontend Quickstart](https://github.com/MichaelCurrin/vue-frontend-quickstart) - a simple site that uses Vue on the frontend without Node or build step.
- [React Quickstart](https://github.com/MichaelCurrin/react-quickstart) - like this project, but using React instead of Vue.
- [Node Project Template](https://github.com/MichaelCurrin/node-project-template) - a more generic Node template.


## License

Released under [MIT](/LICENSE) by [@MichaelCurrin](https://github.com/MichaelCurrin).
