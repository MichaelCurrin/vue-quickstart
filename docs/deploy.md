# Deploy
> How to build and deploy this app


## Test and deploy using GitHub Actions

A production Vue app needs a _build_ step to compile the scripts to plain JavaScript. This output can then be served then a static asset directory, without a Node.js server running.

This project uses a GitHub Actions flow to test, build and deploy the app

That is configured here:

- [main.yml](/.github/workflows/main.yml) workflow

Just **push** or **merge** to master. The workflow will build and deploy the app to the `gh-pages` branch.


## Configure GH Pages

After a successful build, you can configure your site to be served on GitHub Pages as follows:

1. Go to repo _Settings_.
2. Go to _GitHub Pages_ section.
3. Enable the site on `gh-pages` branch `root` directory.
4. Wait for your site to build.
5. Check the Actions tab on the repo for the status of the build.
6. Open the public URL when it is done. e.g. https://MichaelCurrin.github.io/vue-quickstart
