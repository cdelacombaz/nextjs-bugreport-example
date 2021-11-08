# Bug Report

## Working example on "main" branch

I am trying to upgrade my packages. Most importantly, NextJS from 10.0.3 to 12.0.3.

This is a working example with my current versions.

```json
  "dependencies": {
    "@formatjs/intl-getcanonicallocales": "^1.5.6",
    "@formatjs/intl-locale": "^2.4.19",
    "@formatjs/intl-pluralrules": "^4.0.11",
    "next": "10.0.3",
    "react": "17.0.1",
    "react-dom": "17.0.1"
  }
```

## Example with upgraded versions where it is still working on "stillWorking" branch

I tried to upgrade to next@latest directly, then went down to 11 to finally find out that the latest version which was
working with this setup is v10.1.3.

## Example with upgraded versions resulting in error on "bugreport" branch

Upgrading Next to v10.2 or any higher results in following error message: `Module not found: Can't resolve '@formatjs/intl-pluralrules/polyfill/'

I also tried to upgrade the @formatjs packages to latest versions, but still get the same error.
