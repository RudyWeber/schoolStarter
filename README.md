# School Starter

## Usage

`npm start --step=X` to serve the X-th step

## How to support my lib / framework ?

Just add its dependencies and parcel takes care of the rest - except for Angular but you may prefer using `ng cli` instead. (Otherwise you can take a look at [parcel-plugin-angular](https://www.npmjs.com/package/parcel-plugin-angular)).

## How it works

The build relies on [parcel](http://parceljs.org).
Each directory must have a name starting by `step` and contain a file named according to the `main` property of the `package.json`.

## Contraints

This is using `npm` variables which aren't supported by `yarn` so you have to use `npm` for this to work.