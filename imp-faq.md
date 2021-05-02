### Q1. What is difference between `.prettierrc` and `.prettier.config.js`?

Prettier uses cosmiconfig for configuration file support. This means you can configure Prettier via (in order of precedence):

* A "prettier" key in your package.json file.
* A `.prettierrc` file written in JSON or YAML.
* A `.prettierrc.json`, `.prettierrc.yml`, `.prettierrc.yaml`, or `.prettierrc.json5` file.
* A `.prettierrc.js`, `.prettierrc.cjs`, `prettier.config.js`, or `prettier.config.cjs` file that exports an object using module.exports.
* A `.prettierrc.toml` file.

