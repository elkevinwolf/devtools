![version](https://img.shields.io/npm/v/@elkevinwolf/eslint-config-base?style=for-the-badge)
![downloads](https://img.shields.io/npm/dt/@elkevinwolf/eslint-config-base?style=for-the-badge)

# @elkevinwolf/eslint-config-base

⚙️ Kevin Wolf's opinionated [shareable ESLint config](https://eslint.org/docs/developer-guide/shareable-configs).

## Installation

```sh
npm install --save-dev eslint prettier typescript @elkevinwolf/eslint-config-base
```

## Usage

Depending on your preferred way to configure ESLint, you have several options:

- In `package.json`, using the `eslintConfig` property:

```jsonc
{
  // name, scripts, dependencies, etc...
  "eslintConfig": {
    "extends": "@elkevinwolf/base"
  }
}
```

- In `.eslintrc.json` or `.eslintrc`:

```json
{
  "extends": "@elkevinwolf/base"
}
```

- In `.eslintrc.js`:

```js
module.exports = {
  extends: "@elkevinwolf/base",
}
```

- In `.eslintrc.yaml` or `.eslintrc.yml`:

```yml
extends: "@elkevinwolf/base"
```

## Contributing

Read the [contributing guidelines](../../#contributing).

## License

[MIT](../../license)
