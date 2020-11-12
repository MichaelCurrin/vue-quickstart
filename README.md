# Vue.js Quickstart
> Minimal Vue app template which uses CI to deploy to GitHub Pages

[![GH Pages Deploy](https://github.com/MichaelCurrin/vue-quickstart/workflows/GH%20Pages%20Deploy/badge.svg)](https://github.com/MichaelCurrin/vue-quickstart/actions)
[![GitHub tag](https://img.shields.io/github/tag/MichaelCurrin/vue-quickstart)](https://github.com/MichaelCurrin/vue-js-quickstart/tags/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue)](#license)

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

[![View site GH Pages](https://img.shields.io/badge/Demo_site-GH_Pages-green?style=for-the-badge)](https://michaelcurrin.github.io/vue-quickstart/)
[![Use this template](https://img.shields.io/badge/Use_this_template-2ea44f?style=for-the-badge)](https://github.com/MichaelCurrin/vue-quickstart/generate)

</div>

After you've looked at the demo screenshot and site, you are welcome to create your own using the template button. This will fork this project and add it to your repos.


## Documentation
> How to install and run the app and deploy it to GH Pages

<div align="center">

[![View docs](https://img.shields.io/badge/go_to-docs-blue)](/docs/)

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

### Related projects

- [Vue Router Quickstart](https://github.com/MichaelCurrin/vue-router-quickstart/)
- [React Quickstart](https://github.com/MichaelCurrin/react-quickstart/)
- [Node Project Template](https://github.com/MichaelCurrin/node-project-template)


## License

Released under [MIT](/LICENSE).
