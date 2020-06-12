## aframe-popup-component

[![Version](http://img.shields.io/npm/v/aframe-popup-component.svg?style=flat-square)](https://npmjs.org/package/aframe-popup-component)
[![License](http://img.shields.io/npm/l/aframe-popup-component.svg?style=flat-square)](https://npmjs.org/package/aframe-popup-component)

Allows information to appear on the camera when you click on an entity

For [A-Frame](https://aframe.io).

### API

| Property | Description | Default Value |
| -------- | ----------- | ------------- |
|          |             |               |

### Installation

#### Browser

Install and use by directly including the [browser files](dist):

```html
<head>
  <title>My A-Frame Scene</title>
  <script src="https://aframe.io/releases/0.9.2/aframe.min.js"></script>
  <script src="https://unpkg.com/aframe-popup-component@1.0.0/dist/aframe-popup-component.min.js"></script>
</head>

<body>
  <a-scene>
    <a-entity popup="foo: bar"></a-entity>
  </a-scene>
</body>
```

#### npm

Install via npm:

```bash
npm install aframe-popup-component
```

Then require and use.

```js
require('aframe');
require('aframe-popup-component');
```
