<div align="center">
    <a href="https://github.com/softspiders/softspiders">
      <img src="./images/sslogo-from-github-20.png"/>
    </a>
</div>

# Starter for package versioning and publishing by Lerna

Starter for [Lerna](https://lerna.js.org/) monorepo

[![lerna](https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg)](https://lerna.js.org/)

---

## Feature tags

- github
- lerna
- publishing
- starter
- template
- versioning

## Parents

- [- ***publishing***, ***versioning***: lerna](https://github.com/softspiders/lerna)

---
## Authors

[Alexander Lapygin](https://github.com/AlexanderLapygin)

---

## Lerna installation

```
npm install --global lerna
```

---

## Install

Being at the root, execute

```
yarn run bootstrap
```

---

## Updating version

First, change, for example, one of the *index.js* files in one of the subpackage, then do commit according to
[Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/).

Then execute the command:

```
yarn run new-version
```

and then watch the output of Lerna's actions in the terminal window, and finally check the local changes in the
*package.json* and *CHANGELOG.md* files of the updated package and in the [GitHub repository](https://github.com/softspiders/lerna-version-release-starter).

---

## Publishing a new version

Change, for example, one or both of the *index.js* files in the subpackages, then do commit according to
[Conventional commits](https://www.conventionalcommits.org/en/v1.0.0/).

Then execute the command:

```
yarn run publish-version
```

then reply to lerna's query if it need be in the terminal window, then watch the output of Lerna's actions in the
terminal, and finally check the local changes in the *package.json*, *CHANGELOG.md* files of the updated package and the
tags of the new versions in the [GitHub repository](https://github.com/softspiders/lerna-version-release-starter).

---

### License

Licensed under the [MIT license](./LICENSE). 

<div align="center">
    <a href="https://github.com/softspiders/softspiders">SOFTSPIDERS</a>
</div>
