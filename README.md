This repo is a reproduction for minification issue with @zeit/ncc

To reproduce the issue:

- clone this repo
- `npm install` the dependencies
- then run `npm run build`

Notice the output in `dist/index.js` is not minified
