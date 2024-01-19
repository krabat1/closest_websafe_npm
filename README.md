# closest_websafe
## Description:
The Node.js package finds the closest websafe color based on a hexadecimal value.
## Install:
```bash
npm install closest_websafe
```
## Usage:
The module expects a string containing a hexadecimal color and returns the nearest websafe hex string to the input as a string.
```js
const hex2websafe = require('closest_websafe');
let notWebsafeColor = "#DECADE";
let websafeColor = hex2websafe(notWebsafeColor);
// websafeColor now contains '#884444'
```
## Notes:
- Invalid input will throw an error message
- Library uses a linear searching algorithm.
- Self-contained, needs no dependencies.

## License:
ISC