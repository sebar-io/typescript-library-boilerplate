# typescript-library-boilerplate

## About

Boilerplate for typescript library with jest, commitizen, eslint, and github ci/cd to publish on npm

## Commitizen

[Commitizen](https://github.com/commitizen/cz-cli) helps us have consistent commit messages in our repository

```
npm run commit
```

## Typescript

[Typescript](https://www.typescriptlang.org/) gives us type checking

```
npm run build
```

## ESLint

[ESLint](https://typescript-eslint.io/) lets us run linting

`npm run lint`

## Prettier

[Prettier](https://prettier.io/) lets us format our code

```
npm run format
```

```
npm run format:check
```

## Commitlint

[Commitlint](https://commitlint.js.org/) let us lint commit messages

```
npm run commitlint
```

## Husky

[Husky](https://github.com/typicode/husky) lets us use git hooks

- commit-msg: `npm run commitlint`
- pre-commit: `npm run precommit`
- pre-push: `npm run prepush`
