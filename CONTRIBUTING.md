# Contributing

Everyone is welcome to contribute!  Here's some instructions to get started.

## Build

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew bundle
npm install
npm i -g @zeit/ncc

npx prettier index.js --write
npx eslint index.js
ncc build index.js
```
