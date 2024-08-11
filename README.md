# @commitlint
The `@commitlint` library is used to ensure that commit messages in a project adhere to a specified convention, promoting clear and consistent messaging in Git commit history. While it helps enforce professional commit messages by following conventions like Conventional Commits, it is not limited to just

Here’s a step-by-step guide to setting up and using @commitlint to ensure proper and professional commit messages:

## Install @commitlint and Related Packages
First, Install `@commitlint` and its devdependencies in your project. Typically, you'll also install Husky to automate the commit message linting process.

```bash
pnpm add --save-dev @commitlint/cli @commitlint/config-conventional @commitlint/prompt-cli @commitlint/types @types/node husky


## Available Scripts

The following npm scripts are available in this project:

### `prepare`

```bash
pnpm run prepare


### `commit`
pnpm run commit
