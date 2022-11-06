# TypeScript Bootstrap

[![Discord](https://discord.com/api/guilds/258167954913361930/embed.png)](https://discord.gg/WjEFnzC) [![Twitter Follow](https://img.shields.io/twitter/follow/peterthehan.svg?style=social)](https://twitter.com/peterthehan)

A TypeScript bootstrap template with minimal configuration.

## Getting started

1. Run the following commands to bootstrap a TypeScript project in your working directory:

   > Replace `my-typescript-project` in the commands below with your own preferred project name!

   ```
   npx degit peterthehan/typescript-bootstrap my-typescript-project
   ```

   ```
   cd my-typescript-project
   ```

   ```
   npm i
   ```

2. You can run the following commands to verify your setup:

   ```
   npm run lint
   npm run build
   npm test
   ```

   View [package.json](./package.json) for more information.

You're ready to create your own TypeScript project! 🎉

## Reasoning

The following resources detail how the configurations in this `typescript-bootstrap` template were determined:

### Configs

- [.eslintrc.json](./.eslintrc.json)

  - https://typescript-eslint.io/docs/#step-2-configuration
  - https://github.com/prettier/eslint-plugin-prettier#recommended-configuration

- [jest.config.json](./jest.config.json)

  - https://kulshekhar.github.io/ts-jest/docs/getting-started/installation#jest-config-file

- [tsconfig.json](./tsconfig.json)

  - https://www.bayanbennett.com/posts/stop-messing-with-tsconfig

### Actions

- [.github/dependabot.yml](./.github/dependabot.yml)

  - https://docs.github.com/en/code-security/dependabot/dependabot-version-updates/configuration-options-for-the-dependabot.yml-file

- [.github/workflows/codeql-analysis.yml](./.github/workflows/codeql-analysis.yml)

  - https://github.com/github/codeql-action

- [.github/workflows/node.js.yml](./.github/workflows/node.js.yml)

  - https://github.com/actions/starter-workflows/blob/main/ci/node.js.yml
