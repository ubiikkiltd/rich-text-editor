[![Build Status](https://travis-ci.org/digabi/rich-text-editor.svg?branch=master)](https://travis-ci.org/digabi/rich-text-editor)

[![Abitti.dev](https://abitti.dev/images/abittidev_logo.svg)](https://abitti.dev/)

[Abitti.dev](https://abitti.dev)

[Use of Abitti Trademark policy](https://abitti.dev/abitti-trademark.html)

Rich text editor with math support for Finnish Matriculation Examination Board.
Live demo can be found at [https://math-demo.abitti.fi/](https://math-demo.abitti.fi/)

Since v4.0.0, only ES2017 code with ES modules is provided (in the `dist`
directory). If you want to use this library, a bundler such as Webpack or
Rollup is probably needed.

## Dependencies

- MathQuill (https://github.com/digabi/mathquill)
- MathJax-Node
- Bacon
- Jquery
- sanitize-html

## Preliminary setup
1. Install dotenv-cli: `npm install -g dotenv-cli`
2. Ensure that npe is installed: `npm install -g npe`
3. Run npm install: `dotenv -- npm install`
4. Create .env -file
5. Ensure that you have Github PAT that can be used publish modules to Github
6. Copy content from `.example_env` -file and change `CLOUBI_PUBLISH_PACKAGES_PAT` value to your PAT

## Getting started

1. Install [Node.js](https://nodejs.org/en/) 
2. Run `npm install`.
3. Run `npm run dev`.
4. Go to [http://localhost:5000](http://localhost:5000)

## Publishing module to Github
1. Run `dotenv -- npm run publish:cloubi`

## Example of direct usage

Demo: http://digabi.github.io/rich-text-editor/

Source: https://github.com/digabi/rich-text-editor/blob/master/index.html

## Deploy to https://math-demo.abitti.fi/

Update `rich-text-editor` dependency in [https://github.com/digabi/math-demo/](https://github.com/digabi/math-demo/), build and deploy it according to its documentation.

# License

https://opensource.org/licenses/MIT
