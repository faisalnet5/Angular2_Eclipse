# NOTE: All credit of this project work goes to Felip (https://github.com/fcoury). I compiled and edited a bit just to make his # probject compatable with Eclipse.
# ---------------------------------------------------------------------

# Getting started

This is not working with WebPack yet. We are using Typescript's compiler `--watch`
clause to get TypeScript compiled.

To install dependencies and start compiling:

```
npm install
tsc --watch
```

Then run a local filesystem HTTP server:

```
npm install -g live-server
live-server
```

And visit [http://localhost:8080](http://localhost:8080)
