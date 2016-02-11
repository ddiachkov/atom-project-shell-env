# 000-project-shell-env package

This package will automatically load shell environment variables for the opened project. Designed to use with tools such as rvm, direnv, autoenv, etc.

## Installation

```
apm install 000-project-shell-env
```

## FAQ
```
Q: Why does the package name starts with zeroes?
A: To force atom to load this package before all other packages so they can use
   project environment variables.
```

```
Q: Why is this package so slow?
A: Because it is synchronously executes shell script when atom is starting.
```

## Commands

* `project-shell-env:load`
* `project-shell-env:reset`

## Similar packages

* [env-from-shell](https://atom.io/packages/env-from-shell)
* [atomenv](https://atom.io/packages/atomenv)