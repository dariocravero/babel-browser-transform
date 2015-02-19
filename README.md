# babel-browser-transform

Babel browser transform based on https://github.com/facebook/react/blob/master/vendor/browser-transforms.js.

It's pretty much the JSX transformer by Facebook but running your code through Babel, giving you
`ES6` and `ES7` (as well as `JSX`) on-the-fly compilation for free :).

Will pick up any `script` tag with the types `text/babel`, `text/es6`, `text/es7` and `text/jsx`.

It exports `BabelTransform.transform` and `BabelTransform.exec`.

A note on the license. Had to use BSD because that's what React uses.
