# Demacroable

Illuminate components often depends on the "[macroable](https://github.com/illuminate/macroable)" (aka Monkey patching) package.
This package replace the official `illuminate/macroable` package with an empty trait.

This package makes the macroable trait empty and removes the possibility to monkey patch
some illuminate components (using the `Macroable` trait) at runtime, forcing end users to
compose (or inherit) with illuminate components in production or use mocking for tests.

> ! Use at your own risk

## Install

```
composer req bafs/illuminate-demacroable
```
