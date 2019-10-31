# eslint-config-fewlines-js

> :warning: **This package is deprecated in favor of [@fewlines/eslint-config](https://github.com/fewlinesco/eslint-config)**

---

Disclaimer: this package is made for our internal usage and is only open source for convenience so we might not consider _Pull Requests_ or _Issues_.

This package includes the shareable ESLint configuration used by Fewlines javascript and typescript projects.

Extends `eslint:recommended`, `plugin:prettier/recommended`, `plugin:react/recommended`

## Usage

```shell
yarn add -D @fewlines/eslint-config-fewlines-js eslint eslint-config-prettier eslint-plugin-prettier prettier eslint-plugin-react
```


Then add these line to your `package.json`:

```json
"eslintConfig": {
  "extends": "@fewlines/fewlines-js"
}
```

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md).
