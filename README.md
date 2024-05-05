# Typescript Node Package Template (husky, lint-staged, prettier, eslint, commititzen, changelog)

### Turborepo is optional

## Setup

```bash
npm i
npx husky-init
brew install pre-commit
pre-commit install
npm install commitizen -g
commitizen init cz-conventional-changelog --save-dev --save-exact
```

## Commit

```bash
git add .
cz or git cz
```

## Build

```js
npm run build
```

## Test

```js
npm run test
```
