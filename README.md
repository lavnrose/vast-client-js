[![Build Status](https://travis-ci.org/dailymotion/vast-client-js.png)](https://travis-ci.org/dailymotion/vast-client-js)

# VAST Javascript Client
Vast Client JS is a Javascript library for parsing Digital Video Ad Serving Template (VAST) documents as close as possible to the Interactive Advertising Bureau (IAB) specification.

This library provides:

 * A VAST parser, which validates the XML and translates it into a JS object.
 * A VAST tracker, which batches the tracking urls and provides methods for calling them.


Complies with [VAST 3.0 spec](http://www.iab.net/media/file/VASTv3.0.pdf).

## Documentation
See [API](docs/api.md)

## Support
If you need to support legacy browsers (e.g. IE8+), don't forget to include [es5.js](https://github.com/inexorabletash/polyfill/blob/master/es5.js)

## Build / Contribute

See [CONTRIBUTING](CONTRIBUTING.md)
