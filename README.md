## simple-monorepo

This is a simplified example of a monorepo.

Reference:
[Learnin’ Lerna for Monorepos in Node.js](https://medium.com/@chris_14660/learnin-lerna-for-monorepos-in-node-js-5b577bdbf380)

Git Clone it first with:

`git clone https://github.com/vickean/simple-monorepo.git`

Then, install dependencies and bootstrap the submodules:

`npm i && npx lerna bootstrap`

To delete node_modules to re-run bootstrap:

`npx lerna clean`
