
# Webpack 4 HMR without react-hot-loader

Ever wanted to use `webpack-dev-server` without `react-hot-loader`.  I.e. just for plain old ES-whatever code?

This repo does exactly that.  However, instead of calling `webpack` directly from the `package.json`, we instead use the Node API to essentially achieve the same thing.
