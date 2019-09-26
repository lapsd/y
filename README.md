# `y` – Interactively manage your Yarn versions

<!-- [![npm](https://img.shields.io/npm/dt/@lapsd/y.svg?style=flat-square)](https://www.npmjs.com/package/@lapsd/y) -->
<!-- [![npm](https://img.shields.io/npm/dm/@lapsd/y.svg?style=flat-square)](https://www.npmjs.com/package/@lapsd/y) -->
[![npm](https://img.shields.io/npm/v/@lapsd/y.svg?style=flat-square)](https://www.npmjs.com/package/@lapsd/y)
[![npm](https://img.shields.io/npm/l/@lapsd/y.svg?style=flat-square)](https://www.npmjs.com/package/@lapsd/y)

<p align="center">
  <a href="https://nodejs.org/">
    <img alt="Node.js" src="./y-logo.png" width="200" />
  </a>
</p>

## Installation

Since you probably already have `node`, the easiest way to install `y` is through `npm`:

    npm install -g @lapsd/y

## Specifying versions

There are a variety of ways of specifying the target yarn version for `y` commands. Most commands use the latest matching version.

Numeric version numbers need to be complete.

- `1.17.3`

There are labels for two especially useful versions:

- `latest`: newest official release

## Removing versions

Remove some cached versions:

    y rm 0.9.4

Removing all cached versions except the current version:

    y prune

## Remove the installed version

This can be useful to revert to the system version of yarn (if in a different location), or if you no longer wish to use yarn, or are switching to a different way of managing it:

    y uninstall