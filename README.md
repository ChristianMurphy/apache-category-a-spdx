# apache-category-a-spdx

[![NPM Version](https://img.shields.io/npm/v/apache-category-a-spdx.svg)](https://www.npmjs.com/package/apache-category-a-spdx)

Apache Category A approved licenses in a machine readable format using [SPDX](https://spdx.org).

Adapted from <https://www.apache.org/legal/resolved.html#what-can-we-include-in-an-asf-project-category-a>

## Installation

```sh
# NPM
npm install apache-category-a-spdx

# Yarn
yarn add apache-category-a-spdx
```

## Usage

```js
var list = require("apache-category-a-spdx");

for (var i = 0; i < list.length; i++) {
  console.log(list[i]);
}
```
