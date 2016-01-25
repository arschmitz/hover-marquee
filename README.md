# CSS3 Hover MARQUEE [![npm version](https://badge.fury.io/js/hover-marquee.svg)](http://badge.fury.io/js/hover-marquee)
### This is a fork of the html5 marquee by muchweb [https://github.com/muchweb/html5-marquee](https://github.com/muchweb/html5-marquee)
## Installation

- Bower: `bower install hover-marquee`
- NPM: `npm install hover-marquee`

## Usage

### Simple usage:

```html
<div class="marquee" data-marquee="Text contents"></div>
```

### Adjust marquee speed:

|CSS Class|Delay|
|:---:|:---:|
|`.marquee-speed-drowsy`|`30s`|
|`.marquee-speed-slow`|`20s`|
|`.marquee-speed-normal`|`10s` (default)|
|`.marquee-speed-fast`|`7s`|
|`.marquee-speed-swift`|`5s`|
|`.marquee-speed-hyper`|`2s`|

#### Custom speed:

Inherits the speed from the class or inline style

|CSS Class|Delay|
|:---:|:---:|
|`.marquee-speed-custom`|`inherit`|

### Adjust direction:

|CSS Class||
|:---:|:---:|
|`.marquee-direction-left`|Right to left (default)|
|`.marquee-direction-right`|Left to right|
|`.marquee-direction-alternate`|Alternate movement|

### Adjust direction:

|CSS Class||
|:---:|:---:|
|`.marquee-direction-left`|Right to left (default)|
|`.marquee-direction-right`|Left to right|
|`.marquee-direction-alternate`|Alternate movement|

### Vintage effect:

|CSS Class||
|:---:|:---:|
|`.marquee-movement-smooth`|Smooth animation (default)|
|`.marquee-movement-steps20`|Jamming animation|
|`.marquee-movement-steps10`|Jamming animation|

## Building

Requirements:

 - Node.js
 - NPM
 - GNU Make

```bash
make
```

This will create `css` directory.
