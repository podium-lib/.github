# Contributing

Thank you for showing an interest in contributing to Podium ❤️

Podium is divided in a collection of modules, each in their separate repositories. The contribution process is the same for all of them.

## Workflow

Fork the repo(s) you would like to contribute to and make a branch off of `main`.

Commits in your pull request should follow the [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) format.

Repos use [semantic release](https://github.com/semantic-release/semantic-release) to release automatically whenever changes are merged to `main`.

## Documentation

We use JSDoc to generate type definitions. If you're new to that workflow,
[the TypeScript docs](https://www.typescriptlang.org/docs/handbook/jsdoc-supported-types.html)
and [this blogpost by Alex Harri](https://alexharri.com/blog/jsdoc-as-an-alternative-typescript-syntax)
are good starting points.

Documentation for Podiun as a whole is in [podium-lib/podium-lib.github.io](https://github.com/podium-lib/podium-lib.github.io).
If you make changes to an existing feature or add a new one, please also open a pull request with the relevant
documentation to that repo.

For user-facing modules API reference documentation should be on the documentation website, for example:

- `@podium/layout`
- `@podium/podlet`
- `@podium/browser`

For modules users typically don't use directy a `README.md` in the repo is enough.
