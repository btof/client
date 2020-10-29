# client

Repository containing the client's package.json and other important files.
All updates and changes should be made through this repository. 

## Known Issues

* Make sure __jss__ package version is the same version as in [@material-ui/styles package.json](https://github.com/mui-org/material-ui/blob/master/packages/material-ui-styles/package.json)
* Keep __cesium__ at version __1.21.0__ and __@types/cesium__ at __1.47.3__
* Keep __bootstrap__ at version __3.4.1__ because [it is the last version UI Bootstrap supports](https://angular-ui.github.io/bootstrap/)
* Keep __expose-loader__, __imports-loader__, __css-loader__, __webpack__, [__webpack-cli__](https://github.com/webpack/webpack-dev-server/issues/2029#issuecomment-707034614) packages held back because of breaking/syntax changes, need to update use of each.
