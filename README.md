# Put Badging up here

- npm
- downloads
- github actions
- code style prettier
- convential commitizen
- license
- issues

# ESLint (and Prettier) config

## What it does

This setup lints your JavaScript code based on practices. Check the [.eslintrc.js](https://github.com/loonz206/eslint-config-loonz206/blob/main/.eslintrc.js) file to see what is included. Feel free to override the rules that make sense for you.

## Installing

1. In your project folder, run:

```
npm i -D eslint-config-loonz206 # or yarn install --dev eslint-config-loonz206
npx install-peerdeps --dev eslint-config-loonz206
```

2. You will see several dependencies were installed. Now, create (or update) a `.eslintrc` file with the following content:

```js
{
  'extends': [
    'loonz206'
  ]
}
```

3. Copy the [.editorconfig](https://github.com/loonz206/eslint-config-loonz206/blob/main/.editorconfig) file from this repository into your project folder

---

This repository is inspired by [eslint-config-wesbos](https://github.com/wesbos/eslint-config-wesbos).
