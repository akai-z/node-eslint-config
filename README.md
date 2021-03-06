# Node.js ESLint Shareable Config

This is an ESLint shareable config for my Node.js projects.

## Requirements

- Node.js 12.
- ESLint 8.13.0 or higher.

## Installation

Add the package to `package.json` file `devDependencies`.

#### npm
```shell
npm i --save-dev https://git@github.com/akai-z/node-eslint-config
```

#### Yarn
```shell
yarn add --dev akai-z/node-eslint-config
```

## Usage

Extend the shareable ESLint config in your project ESLint config file.  
- For JavaScript projects, extend `@akai-z/eslint-config-node/packages/javascript` module.
```json
"extends": "@akai-z/eslint-config-node/packages/javascript"
```
- For TypeScript projects, extend `@akai-z/eslint-config-node/packages/typescript` module.
```json
"extends": "@akai-z/eslint-config-node/packages/typescript"
```
