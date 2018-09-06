# @linter/cli

This is the CLI for `@linter`.

### Installation

You will need to install the cli and providers for the linting/formatting tools
you wanna use.

```sh
npm i -D @linter/cli @linter/provider-eslint @linter/provider-prettier eslint prettier ...
```

### Usage

```sh
linter [options] [globs..]

// Lint all files in project
linter

// Lint files matched by globs
linter "src/**/*.{js,ts}" "config/**/*.json"

// Format all files in project
linter --fix
```
