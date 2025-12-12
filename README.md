# `@peibb/prettier-config`

> My personal [Prettier](https://prettier.io) config.

## Usage

**Install**:

```bash
$ yarn add --dev @peibb/prettier-config
$ npm install --dev @peibb/prettier-config
$ pnpm add --dev @peibb/prettier-config
```

**Option 1: Edit `package.json`**:

```jsonc
{
  // ...
  "prettier": "@peibb/prettier-config"
}
```

**Option 2: Use with `prettier.config.js`**:

```jsonc
module.exports = require('@peibb/prettier-config');
```

**Option 3: Use with `prettier.config.js` and extend it**:

```jsonc
const lingxiConfig = require('@peibb/prettier-config');

module.exports = {
  ...lingxiConfig,
  // 可以覆盖或添加额外配置
  semi: false
};
```