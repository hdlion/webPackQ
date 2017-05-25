## Protips

1. Naming webpack.config.js to webpack.config.babel.js can help in writing webpack config file in es6 and will get it transpiled to es5.
2. `context` - To find files in a specific directory
3. Flag `-s` supress npm errors.
4. path - Need full path directory
5. publicPath - to load from '/dist/'
6. sourcemaps in webpack - Add property 'devtool'
  a. eval - for dev (Quick rebuild & inline source maps)
  b. source-map - for prod (source-maps have separate files)
7.pathInfo - Adds string info to all require statements in webpack build files. Its kind of lots of string in build files. So, its not recommended in webpack production build.
