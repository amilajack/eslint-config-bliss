eslint-config-bliss
=====================

[![NPM version](https://badge.fury.io/js/eslint-config-bliss.svg?maxAge=25920)](http://badge.fury.io/js/eslint-config-bliss)
[![Dependency Status](https://img.shields.io/david/amilajack/eslint-config-bliss.svg?maxAge=25920)](https://david-dm.org/amilajack/eeslint-config-bliss)
[![npm](https://img.shields.io/npm/dm/eslint-config-bliss.svg?maxAge=25920)](https://npm-stat.com/charts.html?package=eslint-config-bliss)

This project was created to serve as a base config for **general node development**.

It adds integration with:
- [x] ES import/export
- [x] Functional Programming
- [x] Promise's
- [x] Flow
- [x] Jest

It is not intended for the browser. If you wish to use this config for browser development, make sure to install [`eslint-plugin-react`](https://github.com/yannickcr/eslint-plugin-react) and [`eslint-plugin-jsx-a11y`](https://github.com/evcohen/eslint-plugin-jsx-a11y) and add `"browser": true` to the env section of your `.eslintrc`

## Installation
1. Install `eslint-config-bliss`
```bash
npm install --save-dev eslint-config-bliss
```

2. Add it to your `.eslintrc` config:
```json
{
  "extends": "bliss"
}
```
