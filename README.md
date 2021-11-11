# Node TS EXE

This project is a simple demo to create EXE file with Node and TypeScript with coverage tests

To run the source needs to install `yarn`, `ts-node`, `typescript` and `pkg` globally:
```
$ npm install -g yarn ts-node typescript pkg
```

And then, just install dependencies and build the EXE and JS minified
```
$ yarn
$ yarn build-exe
```

The files will be created in the `dist/` folder with the `name` of application defined in the `package.json`
