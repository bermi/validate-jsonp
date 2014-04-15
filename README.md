# validate-jsonp

Command line utility for validating a JSONp URL.

## Installation

    npm install validate-jsonp -g

## Usage

    validate-jsonp "http://example.com/jsonp.js?callback=foo"

Will output VALID or INVALID. If invalid the process will exit with 0.

