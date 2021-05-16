![version](https://img.shields.io/npm/v/@elkevinwolf/prettier-config?style=for-the-badge)
![downloads](https://img.shields.io/npm/dt/@elkevinwolf/prettier-config?style=for-the-badge)

# @elkevinwolf/prettier-config

⚙️ Kevin Wolf's opinionated [shareable Prettier config](https://prettier.io/docs/en/configuration.html#sharing-configurations).

## Installation

```sh
npm install --save-dev prettier @elkevinwolf/prettier-config
```

## Usage

Depending on your preferred way to configure Prettier, you have several options:

- In `package.json`, using the `prettier` property:

```jsonc
{
  // name, scripts, dependencies, etc...
  "prettier": "@elkevinwolf/prettier-config"
}
```

- In `.prettierrc`, `.prettierrc.json`, `.prettierrc.json5`, `.prettierrc.yaml`, or `.prettierrc.yml`:

```json
"@elkevinwolf/prettier-config
```

- In `.prettierrc.js`, `.prettierrc.cjs`, `prettier.config.js` or `prettier.config.cjs`:

```js
module.exports = "@elkevinwolf/prettier-config"
```

## Extending

For extending this configuration, you will need to either use `prettier.config.js` or `.prettierrc.js`, [spread](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/Spread_syntax) the original config and add your overwrites:

```js
module.exports = {
  ...require("@elkevinwolf/prettier-config"),
  // your overwrites...
}
```

## Contributing

Read the [contributing guidelines](../../#contributing).

## License

[MIT](../../license)
