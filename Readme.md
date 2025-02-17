# get-version-util

[![npm version](https://badge.fury.io/js/get-version-util.svg)](https://badge.fury.io/js/get-version-util)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A minimal TypeScript utility that returns the current version of the package.

## Why?
To be used in projects like [importmap-manager](https://github.com/ddavid93/importmap-manager) or
[import-map-overrides](https://github.com/single-spa/import-map-overrides)
and test that the specified package version is actually correct.

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Development](#development)
- [License](#license)

## Installation

```bash
npm install get-version-util
```

## Usage

```typescript
import {getVersion} from 'get-version-util';

const version: string = getVersion(); // returns the installed version
```

## API Documentation

### `getVersion()`
Returns the current version of the package as a string.

Returns: `string`

## Development

### Prerequisites
- Node.js (version 14 or higher)
- npm (version 6 or higher)

### Setup
```bash
npm install
```

### Build
```bash
npm run build
```


## Support
For support, please open an issue in the GitHub repository.

## License
This project is licensed under the MIT License - see the [LICENSE](License.md) file for details