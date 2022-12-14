# null_or_empty

[![Node CI](https://github.com/VitaliiDubinin/null_or_empty/actions/workflows/main.yml/badge.svg)](https://github.com/VitaliiDubinin/null_or_empty/actions/workflows/main.yml)

[![Build Status](https://travis-ci.com/username/projectname.svg?branch=master)](https://travis-ci.com/username/projectname)

![example workflow](https://github.com/github/docs/actions/workflows/main.yml/badge.svg)

![example workflow](https://img.shields.io/maintenance/yes/2022)

A Node.js package that checks, if a given string is null or empty.

## Usage

First, install the package using npm:

    npm install @skalwar/null_or_empty --save

Then, require the package and use it like so:

    var isNullOrEmpty = require('@skalwar/null_or_empty');

    console.log(isNullOrEmpty("")); // true
    console.log(isNullOrEmpty(null)); // true
    console.log(isNullOrEmpty(undefined)); // true

    console.log(isNullOrEmpty("Hello World")); // false

## License

MIT
