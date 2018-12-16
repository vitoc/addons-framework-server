@prudent/server
===============

Server for Prudent add-ons.

This is useful for Prudent add-on developers.

Installing
==========

```
$ npm install --save @prudent/server
```

Usage
=====

```
require('server').start(function(content) {
    //Place parsing functionality here
    //When parsed, output transactions to stdout
});
```