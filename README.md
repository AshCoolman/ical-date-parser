# ical-date-parser

Provides a simple class for parsing iCal formatted dates into native Date objects.

## Installation

```
$ npm install ical-date-parser
```

## Usage

```js
var ICalDateParser = require('ical-date-parser');

new ICalDateParser(icalDate).parse();
```

## Test

Test are run with `tape` by running:

```
$ npm test
```
