# Example of running webR under node

This repo contains an example of importing and running webR under node. The `@r-wasm/webr` npm package contains both CommonJS and ES Module versions of the webR JavaScript loader, and so the following two examples are included,

 * `index.js` loads the CommonJS build of webR using the `require()` function.
 * `index.mjs` loads ES Module build of webR using `import` statement.

## Running the example (Linux/macOS)

* Clone this repo and `cd` into the new directory.
* Install webR: `npm install`, or `npm install @r-wasm/webr`.
* Run the example: `node index.js`, or `node index.mjs`.

If successful, the example will load webR and display 10 normally distributed random numbers,

```
$ node index.mjs
Result of running `rnorm` from webR:  [
  5.353056062381611,
  5.250212064338357,
  6.701975264508905,
  4.524907550257074,
  5.1218367202394255,
  3.6861353558585437,
  4.619462419163489,
  4.900875077530067,
  1.31186251698673,
  5.399812408313427
]
```
