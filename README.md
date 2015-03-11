# jsdom-compat
`jsdom`, locked to a version compatible with node 0.10

[![Build Status](https://travis-ci.org/h5o/jsdom-compat.svg?branch=master)](https://travis-ci.org/h5o/jsdom-compat)

As of v4, `jsdom` is no longer compatible with node 0.10. This package makes it easier 
to do testing for libs that need to work in older versions of node by allowing to 
install two versions of `jsdom` side by side.

`require('jsdom-compat')` returns the `jsdom` itself.
