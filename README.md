# Webpack Development Server Issue

This repo was created in order to reproduce the issue reported in: https://github.com/webpack/webpack-dev-server/issues/2781.

First run: `yarn install`

To see the expected behaviour run: `yarn workspace webpack-4 run start` (look at the value of WEBPACK_DEV_SERVER printed to the console).

To see the new actual behaviour run: `yarn workspace webpack-5 run start` (look at the value of WEBPACK_DEV_SERVER printed to the console).
