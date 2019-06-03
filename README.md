# Adobe Stock API SDK for JavaScript

## Overview
This is a JavaScript/Node SDK for the various APIs provided by the Adobe Stock services.

## Before You Begin
Check out [our Getting Started documentation](https://www.adobe.io/apis/creativecloud/stock/docs.html). At a minimum, you'll need a Stock API Key by [creating a Creative Cloud Adobe Stock integration on console.adobe.io](https://console.adobe.io/integrations/new).

If you only need the built version of the SDK, the `dist` folder contains the files you can download and use without requiring this repository.

### Requirements

- [node.js](https://nodejs.org) v6.3.1 or newer
- [`yarn`](https://yarnpkg.com/en/docs/install)

### Install Dependencies
- `yarn install`

## Build
- `yarn run build`

Creates the JavaScript library file under the `dist/` directory.

## Usage
Check out the [usage documentation](USAGE.md)!

## Running the Test Suite
- `yarn test` ( eslint, mocha )
This also generates code coverage report using karma test runner.

### Linting
- `yarn run lint`
