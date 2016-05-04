# Animated Heat Distortion Effect with WebGL

> Using fragment shaders in WebGL to create an animated heat haze distortion effect on images.

> DEMO: <a href="http://mduplinsky.me/projects/webgl-distortion-effects/">http://mduplinsky.me/projects/webgl-distortion-effects/</a>

## Usage

> SASS

`$ [sudo] gem install sass`

`$ cd webgl-distortion-effects`

First run `$ touch cooking.scss cooking.css`

`$ sass --watch cooking.scss:cooking.css --style compressed` compressed will minify on un-watch

When done:

`Ctrl+C` via Terminal to exit watch

> UglifyJS 2

`$ [sudo] npm install uglify-js -g`

To uncompress `cookin.min.js`

`$ uglifyjs cooking.min.js -b -o cooking.js`

To compress & mangle `cooking.js`

`$ uglifyjs cooking.js -c -m -o cooking.min.js`