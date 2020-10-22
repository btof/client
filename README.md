# client

Repository containing the client's package.json and other important files.
All updates and changes should be made through this repository. 

## Known Issues

* Make sure __jss__ package version is the same version as in [@material-ui/styles package.json](https://github.com/mui-org/material-ui/blob/master/packages/material-ui-styles/package.json)
* Keep __cesium__ at version __1.21.0__ and __@types/cesium__ at __1.47.3__
* Keep __raw-loader__ at version __1.0.0__ due to [breaking change in version 2.0.0](https://github.com/webpack-contrib/raw-loader/blob/master/CHANGELOG.md)
* Keep __bootstrap__ at version __3.4.1__ because [it is the last version UI Bootstrap supports](https://angular-ui.github.io/bootstrap/)
* Keep webpack-cli at version __3.3.12__ because [v4 still has issues](https://github.com/webpack/webpack-dev-server/issues/2029#issuecomment-707034614)
