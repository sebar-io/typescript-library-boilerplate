# typescript-library-boilerplate

## About

Boilerplate for typescript library with jest, commitizen, eslint, and github ci/cd to publish on npm

## Commitizen

[Commitizen](https://github.com/commitizen/cz-cli) helps us have consistent commit messages in our repository

```bash
npm run commit
```

## Typescript

[Typescript](https://www.typescriptlang.org/) gives us type checking

```bash
npm run build
```

## ESLint

[ESLint](https://typescript-eslint.io/) lets us run linting

```bash
npm run lint
```

## Prettier

[Prettier](https://prettier.io/) lets us format our code

```bash
npm run format
```

```bash
npm run format:check
```

## Jest

[Jest](https://jestjs.io/) lets us run automated test cases

```bash
npm run test
```

## Commitlint

[Commitlint](https://commitlint.js.org/) let us lint commit messages

```bash
npm run commitlint
```

## Husky

[Husky](https://github.com/typicode/husky) lets us use git hooks

- commit-msg: `npm run commitlint`
- pre-commit: `npm run precommit`
- pre-push: `npm run prepush`

# lint-staged

[lint-staged](https://github.com/okonet/lint-staged) lets us run eslint and prettier on our staged files

## GitHub Actions

[GitHub Actions](https://github.com/features/actions) lets us automate workflows in our repository

[integration.yml](https://docs.github.com/en/actions/automating-builds-and-tests/building-and-testing-nodejs) lets us build and test our code whenever we create a pull request or push to main
