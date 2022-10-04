# NPM package bootrapper

This package is used as template to create new npm packages

## .npmrc contents
```
@[scope]:registry=https://npm.pkg.github.com <br>
npm.pkg.github.com/:_authToken=[token]
```

## Build your package
```bash
yarn run build
```

## Test your package
```bash
yarn run test
```

## Create a new package
```bash
git add -A; git commit -m "Commit name"
git push
```

*to publish*:
```bash
yarn publish
```

for more information please see here:

https://itnext.io/step-by-step-building-and-publishing-an-npm-typescript-package-44fe7164964c