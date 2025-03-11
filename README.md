# Eslint-Config

> Eslint Config for Mints Component

## Compatibility

- **Version 2.x+**: Supports **ESLint 9+** and uses the new [Flat Config](https://eslint.org/docs/latest/use/configure/configuration-files-new).
- **Version 1.x**: Compatible with **ESLint 8** and uses the traditional `.eslintrc` configuration.

## Installation

Install the latest version (for ESLint 9+):

```shell
yarn add @mints/eslint-config --dev
```

If you're using ESLint 8, please install version 1.x:

```shell
yarn add @mints/eslint-config@1 --dev
```

## Usage

For ESLint 9+ (Flat Config):

Create an `eslint.config.js` file:

```javascript
import mintsConfig from '@mints/eslint-config';

export default mintsConfig;
```

For ESLint 8 (Legacy Config):

In your `.eslintrc.*`:

```json
{
  "extends": ["@mints/eslint-config"]
}
```

## License

MIT
