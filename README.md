# eslint-config-fewlines-js

Disclaimer: this package is made for our internal usage and is only open source for convenience so we might not consider _Pull Requests_ or _Issues_.

This package includes the shareable ESLint configuration used by Fewlines javascript and typescript projects.

Extends `eslint:recommended`, `plugin:prettier/recommended`, `plugin:react/recommended`

## Usage

This package is meant to be used with `@fewlines/front-scripts`, if you do, you only have to install this one package:

```shell
yarn add -D @fewlines/front-scripts
```

Then add these line to your `package.json`:

```json
"eslintConfig": {
  "extends": "fewlines-js"
}
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
