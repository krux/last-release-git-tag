# last-release-git-tag
---
[![Dependency Status](https://david-dm.org/semantic-release/last-release-git-tag.svg)](https://david-dm.org/semantic-release/last-release-git-tag)
[![devDependency Status](https://david-dm.org/semantic-release/last-release-git-tag/dev-status.svg)](https://david-dm.org/semantic-release/last-release-git-tag#info=devDependencies)
[![js-standard-style](https://img.shields.io/badge/code%20style-standard-brightgreen.svg?style=flat)](https://github.com/feross/standard)

## Installation

To install this plugin, execute:

```shell
npm install --save-dev @krux/last-release-git-tag
```

## Usage

To use this plugin, modify your `package.json` as follows:

```
"release": {
  "getLastRelease": "./node_modules/@krux/last-release-git-tag",
}
```

If you have existing releases, ensure they start with `v` as in `v1.0.0`.
