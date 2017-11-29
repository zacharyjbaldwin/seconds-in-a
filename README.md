# seconds-in-a
A small library used to quickly reference the number of seconds in a given amount of time.

## Usage

Setting browser cookies:
```javascript
var secondsInA = require('seconds-in-a');

// example when setting browser cookies
cookie: {
    maxAge: secondsInA.month; // sets the max age property of the cookie to 28 days.
};
```

Properties:

```javascript
secondsInA.minute => 60
secondsInA.hour => 3600
secondsInA.day => 86400
secondsInA.week => 604800
secondsInA.month => 2620800
secondsInA.year => 31449600
secondsInA.decade => 314496000
secondsInA.generation => 786240000
secondsInA.century => 3144960000
```

## License
MIT