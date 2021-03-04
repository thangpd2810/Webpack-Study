# Webpack-Study
Note here ...

WEBPACK DEPENDENCIES:
+ webpack: Bundles modules into (.js, .css, .jpg, .png) static assets, ready to be read by browser.
+ webpack-dev-server: Để tạo dev server như localhost:8080 cùng với live-reloading. Có thể config lại dev server trong webpack.config.js --> devServer.

# Tip: 
webpack-dev-server serves bundled files from the directory defined in output.path, i.e., files will be available under http://[devServer.host]:[devServer.port]/[output.publicPath]/[output.filename]