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

## Switching versions

Switching from a version to another:

    y

## Adding specifying versions

There are a variety of ways of specifying the target yarn version for `y` commands. Most commands use the latest matching version.

Numeric version numbers need to be complete:

- `1.17.3`

There are labels for versions:

- `latest`: newest official release

## Removing versions

Remove some cached versions:

    y rm 0.27.5

Removing all cached versions except the current version (coming soon):

    y prune

## Remove the installed version (coming soon)

This can be useful to revert to the system version of yarn (if in a different location), or if you no longer wish to use yarn, or are switching to a different way of managing it:

    y uninstall

## For more help

Check all available commands:

    y --help

## TODOs

- [ ] Add command: `y uninstall`
- [ ] Add command: `y prune`
- [ ] Add security step when downloading a new Yarn version