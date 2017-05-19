This project contains core maps for [ords-core](https://github.com/MedSolve/ords-core)

# Gitter Channel
[Chat in Gitter](https://gitter.im/GallVp/chiroit-backend?utm_source=share-link&utm_medium=link&utm_campaign=share-link)

# Using this module
This module exists on npm. To use it run:

```
npm install @ords/modules --save
```

# Global dependencies
- nodejs
- typescript
- typings
- mocha

# Getting started
Initially install dependencies by running:
```
npm run build-env
```
Whenever you have made changes you can run the following command
```
npm run build-depoly
```
## Scripts
In order to test the project you can now run:
```
npm test
```
To clean the project do:
```
npm run clean
```

# Contribution
Below are some general rules of code:

- Use camleCase instead of underscore
- Document your code with comments
- Write at least unit tests
- Follow established directory structure

All maps from microservices to connector should be named acording to what connector they belong to. Please see the names of already implemented maps and follow that naming.

# Versioning
We use schemantic versioning. Do no introduce backwards compatible breakable code without upgrading the software version to a major release.