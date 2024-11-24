# redark

A dark theme for [Redoc](https://github.com/Redocly/redoc)

[Check out this demo!](https://pages.dilanxd.com/redark)

## Installation

First, install from npm:

```
$ npm i redark-theme
```

Then, add the script and stylesheet from `node_modules` to your HTML:

```html
<link rel="stylesheet" href="node_modules/redark-theme/redark.css" />

<script src="node_modules/redark-theme/redark.js"></script>
```

Finally, initialize Redoc with the `redark` theme:

```html
<body>
  <div id="redoc-container"></div>
  <script src="https://cdn.redoc.ly/redoc/latest/bundles/redoc.standalone.js"></script>
  <script>
    Redoc.init(
      'url/to/your/spec',
      { theme: redark },
      document.getElementById('redoc-container')
    );
  </script>
</body>
```

You can also access the theme object in JavaScript:

```js
import { theme } from 'redark-theme';

// use with the Redoc React component or something
```
