![version](https://img.shields.io/npm/v/@elkevinwolf/eslint-config-react?style=for-the-badge)
![downloads](https://img.shields.io/npm/dt/@elkevinwolf/eslint-config-react?style=for-the-badge)

# @elkevinwolf/eslint-config-react

⚙️ Kevin Wolf's opinionated [shareable ESLint config](https://eslint.org/docs/developer-guide/shareable-configs) for [React](https://reactjs.org) projects.

## Installation

```sh
npm install --save-dev eslint prettier typescript @elkevinwolf/eslint-config-react
```

## Usage

Depending on your preferred way to configure ESLint, you have several options:

- In `package.json`, using the `eslintConfig` property:

```jsonc
{
  // name, scripts, dependencies, etc...
  "eslintConfig": {
    "extends": "@elkevinwolf/react"
  }
}
```

- In `.eslintrc.json` or `.eslintrc`:

```json
{
  "extends": "@elkevinwolf/react"
}
```

- In `.eslintrc.js`:

```js
module.exports = {
  extends: "@elkevinwolf/react",
}
```

- In `.eslintrc.yaml` or `.eslintrc.yml`:

```yml
extends: "@elkevinwolf/react"
```

## Contributing

Read the [contributing guidelines](../../#contributing).

## License

[MIT](../../license)
