# Usage
> How to run the app locally


## Run

Compile and start a hot-reloading dev server.

```sh
$ yarn start
```

Open in the browser:

- https://localhost:8080


## Build

Compile and minify for production.

```sh
$ yarn build
```

Now you can view the output in the unversioned `dist` directory.


## Lint and format

Detect errors and warnings and fix where possible.

```sh
$ yarn lint:fix
```

Run checks but do not fix up. Warnings will pass, but any errors will cause an error exit status - this is useful for a CI/CD flow.

```sh
$ yarn lint:check
```


## Customize

See [Configuration Reference](https://cli.vuejs.org/config/).

In order to serve on a subpath on GH Pages, the project name is set as a subpath in [vue.config.js](/vue.config.js). See the [Vue config](https://cli.vuejs.org/config/#target-browsers) docs.

Optionally add this to `.gitignore`. This is based on the Vue CLI quickstart.

```
.env.local
.env.*.local
```
