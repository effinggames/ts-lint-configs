# ts-lint-configs

Standardized configs for tslint and prettier.

Fork of tslint-config-airbnb to make it a bit stricter and upgrade tslint-microsoft-contrib.

## Installation

```sh
npm install @effinggames/ts-lint-configs --save-dev
```

## Usage

In `tslint.json`:

```json
{
  "extends": "@effinggames/ts-lint-configs"
}
```

In `.prettierrc.js`:
```js
module.exports = require('@effinggames/ts-lint-configs/prettier');
```

### Rules

- [tslint](https://www.npmjs.com/package/tslint)
- [tslint-consistent-codestyle](https://www.npmjs.com/package/tslint-consistent-codestyle)
- [tslint-eslint-rules](https://www.npmjs.com/package/tslint-eslint-rules)
- [tslint-microsoft-contrib](https://www.npmjs.com/package/tslint-microsoft-contrib)

## License

Apache 2.0
