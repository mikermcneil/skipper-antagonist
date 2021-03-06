# [<img title="skipper-antagonist - Antagonistic adapter for Skipper" src="http://i.imgur.com/P6gptnI.png" width="200px" alt="skipper emblem - face of a ship's captain"/>](https://github.com/balderdashy/skipper-antagonist) Antagonistic Adapter

[![Build Status](https://travis-ci.org/balderdashy/skipper-antagonist.svg?branch=master)](https://travis-ci.org/balderdashy/skipper-antagonist)

Fake adapter for receiving streams of file streams. Simulates a slow drain which will always be slower than incoming file uploads.  This provides a worst-case-scenario test case to ensure backpressure mechanisms are functioning properly, helping to protect us against memory overflow issues with streaming multipart file uploads via [Skipper](github.com/balderdashy/skipper).



========================================

## Contribute

See `CONTRIBUTING.md`.



========================================

### License

**[MIT](./LICENSE)**
&copy; 2013, 2014-

[Mike McNeil](http://michaelmcneil.com), [Balderdash](http://balderdash.co) & contributors

See `LICENSE.md`.

This module is part of the [Sails framework](http://sailsjs.org), and is free and open-source under the [MIT License](http://sails.mit-license.org/).


![image_squidhome@2x.png](http://i.imgur.com/RIvu9.png)


[![githalytics.com alpha](https://cruel-carlota.pagodabox.com/a22d3919de208c90c898986619efaa85 "githalytics.com")](http://githalytics.com/balderdashy/skipper-antagonist)
