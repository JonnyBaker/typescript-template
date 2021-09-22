# Typescript Template Project

This repository contains a basic project setup for Typescript development, with Jest and linting pre-configured. Limited VSCode configuration has also been setup to aid with development.

## Pre-configured tools

- _Typescript_ - Configured to allow both TS and JS development. The later is useful, as TS is much simpler to configure and manage than an equivalent Babel setup.
- _ESLint with Prettier_ - Code linting and styling with the most common tools in the industry. The use of the two, allows each of them to focus on doing what they specialise in; whilst the configuration allows them to be run with a single `npm run lint` command (or `:fix` variant).
- _Jest_ - Unit testing framework, configured with `ts-jest` to enable out of the box Typescript support

## Optional Requirements

- NVM with install script - the repository contains a `.nvmrc` file to ensure that the correct version of Node is installed as entering the directory on the command line
- VSCode - this repository assumes that development will be done within VSCode, due to the `.vscode/settings.json` file. This config automatically runs `eslint` on a file save as well as disabling VSCode's auto-detection of tab-sizing
- EditorConfig plugin for VSCode - This defines editor configuration, which atm is just tab sizing. This can be installed by running `ext install EditorConfig` in the `cmd+P` context menu
