# ⌗ json-to-csv-download
A function to easily generate csv downloads of your json data. ✨

[![npm package version](https://badge.fury.io/js/json-to-csv-download.svg)](https://www.npmjs.com/package/json-to-csv-download)&nbsp;
[![npm downloads](https://img.shields.io/npm/dm/json-to-csv-download.svg)](https://www.npmjs.com/package/json-to-csv-download)&nbsp;
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg)](https://prettier.io)

## Live Demo 
[https://json-to-csv-download.coston.io](https://json-to-csv-download.coston.io)

## Features
- Create a csv download from json data
- Lightweight
- Easy to use
- optional filename

## Install

Install with npm:
```sh
npm i json-to-csv-download
```
Or load from a CDN:
```html
<script src="https://cdn.jsdelivr.net/npm/json-to-csv-download"></script>
```

## Example Usage
```html
import csvDownload from 'json-to-csv-download'

...

  <button onClick={() => csvDownload(mockData)}>
    Download Data
  </button>
```

## Arguments

| Prop      | Type      | Argument     | Default | Description                                         |
| --------- | --------- | ------------ | ------- | --------------------------------------------------- |
| data     | `array`  | `required` | `null`  | object or array of objects             |
| filename| `string`  | `optional` | "export.csv"  | The complete filename          |

## Contributing

Please help provide good data faster! Submit any issues and/or make a pull request!