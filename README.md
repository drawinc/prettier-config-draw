# prettier-config-draw

Shared configuration for prettier in draw projects.

## Installation

```shell
# npm
npm install -D -E drawinc/prettier-config-draw

# yarn
yarn add -D -E drawinc/prettier-config-draw
```

Then add to your `package.json` and `prettierrc.js` like this.

```json
"prettier": "github:drawinc/prettier-config-draw"
```

```js
const prettierConfigDraw = require('prettier-config-draw');

module.exports = {
  ...prettierConfigDraw,
};
```
