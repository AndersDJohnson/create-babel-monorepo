# create-babel-monorepo

Like `create-react-app` and [create-babel](https://github.com/AndersDJohnson/create-babel), but for a basic Babel _monorepo_ setup.

Create an app in a new `./my-app` directory:

```shell
$ npm init babel-monorepo my-app
```
[<kbd>copy</kbd>](https://copyhaste.com/c/?t=npm%20init%20babel-monorepo%20my-app)

See [base-create-monorepo](https://github.com/AndersDJohnson/base-create-monorepo) for all CLI options.

* :sparkles: Auto-installs dependencies.
- :sparkles: Auto-initializes `lerna`.
* :fast_forward: Out-of-the-box [preset-env](https://babeljs.io/docs/en/babel-preset-env) for modern syntax & [transform-runtime](https://babeljs.io/docs/en/babel-plugin-transform-runtime) for `async`/`await`.
* 🛠️ Baked-in `build` and `build:watch` scripts, `.gitignore` & more!
