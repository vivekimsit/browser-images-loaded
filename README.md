# browser-images-loaded [![XO code style](https://img.shields.io/badge/code_style-XO-5ed9c7.svg)](https://github.com/sindresorhus/xo)

> Check if all images in the parent element are loaded


## Usage

```js
const imagesLoaded = require('browser-images-enabled');

imagesLoaded(selectorString).then(res => {
  console.log(res); // (true|false)
})
.catch(err => console.error(err));
```

## License

MIT © [Vivek Poddar](http://github.com/vivekimsit)
