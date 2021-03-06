minor-branch
============

[![Build Status](https://travis-ci.org/mwinche/minor-branch.svg)](https://travis-ci.org/mwinche/minor-branch) [![Coverage Status](https://coveralls.io/repos/mwinche/minor-branch/badge.svg?branch=master&service=github)](https://coveralls.io/github/mwinche/minor-branch?branch=master)

Utility which automates the creation of a minor version branch whenever a
new major or minor version is made.

## Installation

To install run `npm install --save-dev minor-branch`.

Then edit your package.json to have the following run script:

```json
	"scripts": {
		"postversion": "minor-branch",
		...
	}
```

## IMPORTANT NOTE

This utility requires a minimum npm version of 2.13.0! Prior to this postversion
scripts (among others) were not given the access this utility needs.

## Development

Simply checkout the source, run `npm install` to set up the project and `npm test` to run tests.

## License

MIT License

