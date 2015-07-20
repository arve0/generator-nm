# <%= moduleName %> [![Build Status](https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>.svg?branch=master)](https://travis-ci.org/<%= githubUsername %>/<%= moduleName %>) [![npm version](https://badge.fury.io/js/<%= moduleName %>.svg)](http://badge.fury.io/js/<%= moduleName %>)

> My <%= superb %> module


## Install

```
$ npm install --save <%= moduleName %>
```


## Usage

```js
var <%= camelModuleName %> = require('<%= moduleName %>');

<%= camelModuleName %>('unicorns');
//=> unicorns & rainbows
```
<% if (cli) { %>

## CLI

```
$ npm install --global <%= moduleName %>
```
```
$ <%= moduleName %> --help

  Usage
    <%= moduleName %> [input]

  Example
    <%= moduleName %>
    unicorns & rainbows

    <%= moduleName %> ponies
    ponies & rainbows

  Options
    --foo  Lorem ipsum. Default: false
```
<% } %>

## License

MIT © [<%= name %>](<%= website %>)
