# raven-blacklist

> [Raven](https://github.com/getsentry/raven-js) options to ignore common errors from 3rd party scripts / browser extensions

## Install

```bash
npm install raven-blacklist
```

## Usage

```js
var errorTrackingOptions = require('raven-blacklist')
Raven.config(YOUR_SENTRY_URL, errorTrackingOptions)
```

## Sources

- https://gist.github.com/impressiver/5092952
- https://gist.github.com/there4/5224975
- https://gist.github.com/bcambel/8383965
- https://gist.github.com/tachiba/30c5f2d1194ccdbd4e54
- https://github.com/getsentry/raven-js/blob/master/docs/tips.rst#decluttering-sentry

## Licence

MIT
