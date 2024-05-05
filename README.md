# Typescript Node Package Template (husky, lint-staged, prettier, eslint, commititzen, changelog, vitest)

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

### Turborepo is optional

## Setup

```bash
npm i
npx husky-init
brew install pre-commit
pre-commit install

```

## Commit

```bash
git add .
git commit -m /(?s)(build|ci|docs|feat|fix|perf|refactor|style|test|chore|revert|bump)(\(\S+\))?!?:( [^\n\r]+)((\n\n.*)|(\s*))?$/
```

## Build

```js
npm run build
```

## Test

```js
npm run test
```
