# test-assets

Public distribution repository for testing tools, packages and assets by [Dontenwill AG](https://github.com/dontenwill-standard).

This repository serves as the public registry for npm packages, executables and other files used in automated testing. Source code is maintained in private repositories.

## Packages

| Package | Description |
|---------|-------------|
| [`@dontenwill-standard/be-portal-playwright-helpers`](./packages/be-portal-playwright-helpers) | Playwright helper classes for be-portal GUI tests |

## Installation

Packages are published to the GitHub Packages npm registry. Add the following to your `.npmrc`:

```
@dontenwill-standard:registry=https://npm.pkg.github.com
```

Since this repository is public, packages can be installed without authentication:

```bash
npm install @dontenwill-standard/be-portal-playwright-helpers
```

## Contributing

This is a distribution-only repository. Please do not open pull requests with source code changes here. For bug reports or feature requests, contact the maintainers directly.
