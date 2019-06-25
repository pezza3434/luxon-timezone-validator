# luxon-timezone-validator

Validates timezones to check they're compatible with the Luxon library. Will also suggest alternatives if required.

## Install

Available on NPM

npm install luxon-timezone-validator

## API
```js
const { isValidWithLuxor, suggestAlternativeTimezone } = require('luxon-timezone-validator');
const validTimezone = isValidWithLuxor(yourTimezone) || suggestAlternativeTimezone(yourTimezone);
```
