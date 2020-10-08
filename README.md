# glsl-utils

glsl utility functions  
Depends on [glslify](https://github.com/glslify/glslify).

## Install

```
npm i git://github.com/akakuro43/glsl-utils.git
```

## How to use

### `random(vec2 p)`

calculate white noise.

```
#pragma glslify: random = require(glsl-util/random);
```

### `hsvToRgb(vec3 hsv)`

```
#pragma glslify: convertHsvToRgb = require(glsl-util/convertHsvToRgb);
```

### `rgbToHsv(vec3 rgb)`

```
#pragma glslify: convertRgbToHsv = require(glsl-util/convertRgbToHsv);
```

