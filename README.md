# @orkans/prettier-config `v1.0.0`

My personal [Prettier](https://prettier.io) config.


## Usage

**Install**:

```bash
$ npm i @orkans/prettier-config --save-dev
```

**Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@orkans/prettier-config"
}
```

If you don’t want to use `package.json`, you can use prettier config file to export a string, e.g.:

**`.prettierrc.json`**:
```jsonc
"@orkans/prettier-config"
```
You can mix default options with your own in `.prettierrc.js`:
```js
module.exports = {
  ...require('@orkans/prettier-config'),
  tabWidth: 4,
  semi: false,
};
```

## Links
Prettier:
- [Configuration File](https://prettier.io/docs/en/configuration.html)
- [Options](https://prettier.io/docs/en/options)

## Author
[Orkan](https://github.com/orkan)

## License
MIT
