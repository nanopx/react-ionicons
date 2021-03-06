# A React Ionicon Component

<p align="center">
  <img src="https://raw.githubusercontent.com/zamarrowski/react-ionicons/master/ionicons-logo.png">
</p>

View page: https://zamarrowski.github.io/react-ionicons/

## Install

```sh
$ npm install --save react-ionicons
```

## Usage

```js
import React from 'react'
import { render } from 'react-dom'
import Ionicon from 'react-ionicons'

render(
  <Ionicon icon="ion-home" fontSize="35px" color="red"/>
  <Ionicon icon="ion-cloud" rotate={true} fontSize="35px" color="blue"/>
  <Ionicon icon="ion-cloud" fontSize="35px" color="#C9C9C9"/>
  <Ionicon icon="ion-cloud" fontSize="35px" color="rgb(125, 176, 24)"/>
  <Ionicon icon="ion-refresh" rotate={true} fontSize="35px" color="rgb(125, 176, 24)"/>
, document.getElementById('container'))
```

### Browserify

[`browserify`](https://npmjs.com/packages/browserify) is supported, but you have to install [`browserify-css@^0.12.0`](https://npmjs.com/packages/browserify-css) manually.

## Features

* No dependencies, just React.
* SVG Icons.
* Simple API.
* Animations.
* Customizable.
* Support to Create React App.

## API:

| Param | Type | Description | Example |
| --- | --- | --- | --- |
| `icon` | `String` | Icon of ionicons. See http://ionicons.com/. | `icon="ion-home"` |
| `className` | `String` | Name of a CSS class | `className="myClass"` |
| `fontSize` | `String` | Icon size. Allow all units (px, em, %, pt...). | `fontSize="35px"` |
| `color` | `String` | Icon color. Allow string (blue, red, cyan...), rgb, rgba and hexadecimal colors. | `color="#C9C9C9"` |
| `rotate` | `Boolean` | Apply rotate animation to icon | `rotate={true}` |
| `shake` | `Boolean` | Apply shake animation to icon | `shake={true}` |
| `beat` | `Boolean` | Apply beat animation to icon | `beat={true}` |
