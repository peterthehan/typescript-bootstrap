# TypeScript Bootstrap

[![Discord](https://discord.com/api/guilds/258167954913361930/embed.png)](https://discord.gg/WjEFnzC) [![Twitter Follow](https://img.shields.io/twitter/follow/peterthehan.svg?style=social)](https://twitter.com/peterthehan)

A TypeScript bootstrap template with minimal configuration.

## Getting started

Run the following commands to bootstrap a TypeScript project in your working directory:

```
npx degit peterthehan/typescript-bootstrap my-typescript-project
```

```
cd my-typescript-project
```

```
npm i
```

You're ready to create your own TypeScript project! 🎉

You can run the following commands to verify your setup:

```
npm run lint
npm test
npm run build
```

View [package.json](./package.json) for more information.

## Reasoning

The following resources detail how the the configurations in this `typescript-bootstrap` template was determined.

1. [.eslintrc.json](./.eslintrc.json)

   - https://github.com/typescript-eslint/typescript-eslint/blob/master/docs/getting-started/linting/README.md#configuration
   - https://github.com/prettier/eslint-plugin-prettier#recommended-configuration

2. [jest.config.json](./jest.config.json)

   - https://kulshekhar.github.io/ts-jest/docs/getting-started/installation#jest-config-file

3. [tsconfig.json](./tsconfig.json)

   - https://www.bayanbennett.com/posts/stop-messing-with-tsconfig
