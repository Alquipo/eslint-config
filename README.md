<div align="center">
  <a href="https://eslint.org/">
    <img height="150" src="https://eslint.org/assets/images/logo/eslint-logo-color.svg">
  </a>

  <h1>@alquipo/eslint-config </h1>
</div>

<p align="center">

  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/Alquipo/eslint-config">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/Alquipo/eslint-config">

  <a href="https://www.linkedin.com/in/alquiponeto/">
      <img alt="Made by Alquipo" src="https://img.shields.io/badge/made%20by-AlquipoNeto-blue">
  </a>

  <a href="https://github.com/Alquipo/eslint-config/commits/master">
      <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/Alquipo/eslint-config?color=blue">
  </a>

  <img alt="License" src="https://img.shields.io/badge/license-MIT-brightgreen?color=blue">

  <img alt="CI Workflow" src="https://github.com/Alquipo/eslint-config/actions/workflows/release-package.yml/badge.svg">

</p>

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;
- Import plugin
- Import Helpers plugin
- Storybook plugin
- Next plugin

### Install

First, install it:

```bash
$ npm install --save-dev eslint @alquipo/eslint-config 
```
or

```bash
$ yarn add -D eslint @alquipo/eslint-config 
```

### Usage

Add `@alquipo/eslint-config ` to the extends section of your `.eslintrc` or `package.json` file. 

##### React Project 

```json
{
  "extends": "@alquipo/eslint-config/react"
}
```

or

```json
{
   "scripts": {
      "lint": "eslint"
  },
  "devDependencies": {
    "eslint": "^8.25.0",
    "@alquipo/eslint-config": "^1.0.1"
  },
  "eslintConfig": {
    "extends": "@alquipo/eslint-config/react"
  },
}
```
##### Next Project 

```json
{
  "extends": "@alquipo/eslint-config/next"
}
```
or


```json
{
   "scripts": {
      "lint": "next lint"
  },
  "devDependencies": {
    "eslint": "^8.25.0",
    "@alquipo/eslint-config": "^1.0.1"
  },
  "eslintConfig": {
    "extends": "@alquipo/eslint-config/next"
  },
}
```

## 🤔 How to contribute to the project

- Make a **fork**;
- Create a new branch with your changes: `git checkout -b my-feature`
- Save the changes and create a commit message telling what you've done:`git commit -m "feature: My new feature"`
- Submit your changes: `git push origin my-feature`

> If you have any questions, check out this [guide on how to contribute on GitHub](https://github.com/firstcontributions/first-contributions)

## 📝 License

This project is MIT [Licensed](https://opensource.org/licenses/MIT).

Made with ❤️ by Alquipo Neto 👋🏽 [Contact!](https://www.linkedin.com/in/alquiponeto/)