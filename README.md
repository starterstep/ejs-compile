ejs-compile
=================

Pre-compile all your .ejs files to requirable js files.  Sorry does not work on Windows :(

## Installation
```
  $ [sudo] npm install -g ejs-compile
```

## Pre-compile all your ejs files recursively

```
  $ ejs-compile <dir>
```

## Render your html

```
  //template.ejs has previously been compiled to template.js
  var Template = require('./template');
  var html = Template({
    title:'Pre-compiling is cool'
  });

```
