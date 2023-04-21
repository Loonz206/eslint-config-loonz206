![NPM downloads](https://img.shields.io/npm/dm/eslint-config-loonz206)
![GitHub issues](https://img.shields.io/github/issues/loonz206/eslint-config-loonz206)
[![Github Actions CI](https://github.com/Loonz206/eslint-config-loonz206/actions/workflows/ci.yml/badge.svg?branch=main)](https://github.com/Loonz206/eslint-config-loonz206/actions/workflows/ci.yml)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
![Code Style Prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)
![MIT License](https://img.shields.io/badge/license-MIT-red.svg?style=flat)

# eslint-config-loonz206

## What it does

This setup lints your JavaScript code based on practices. Check the [.eslintrc.js](https://github.com/loonz206/eslint-config-loonz206/blob/main/.eslintrc.js) file to see what is included. Feel free to override the rules that make sense for you.

## Installing

1. In your project folder, run:

```
npm i -D eslint-config-loonz206
```

or for `yarn`

```
yarn install --dev eslint-config-loonz206
```

then run

```
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

3. Copy the [.editorconfig](https://github.com/loonz206/eslint-config-loonz206/blob/main/.editorconfig) file from this repository into your project folder, and be sure you have eslint and prettier installed

---

This repository is inspired by [eslint-config-wesbos](https://github.com/wesbos/eslint-config-wesbos).
