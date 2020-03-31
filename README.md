<!-- https://github.com/streamich/react-use/blob/master/README.md -->
<div align="center">
  <h1>
    <br>
    <br>
    .eslintrc.js 🧹
    <br>
    <br>
    <br>
    <br>
  </h1>
</div>

<!-- ![](https://img.shields.io/badge/eslint-passing-brightgreen) ![](https://img.shields.io/badge/jest-passing-brightgreen) -->

<br>

**.eslintrc.js formats your JavaScript code for you, so you can focus on what matters.** Most people think of ESLint as an annoying linter that simply yells at you every time you screw something up. 🥵 But did you know of all the rules ESLint supports, just less than 100 can fix your code, too? `.eslintrc.js` is just such a configuration file to make ESLint _extremely useful_ and productive.

The configuration preferences themselves are heavily inspired by `gofmt`, the delightful Go language formatter. Each and every rule this configuration uses for auto-formatting was carefully considered. More than that, [I myself](https://twitter.com/username_ZAYDEK) rely on this configuration file _everyday_ and maintain the preferences as needed.

## Installation

All you need to do to get started is the following:

```sh
curl https://raw.githubusercontent.com/codex-src/dot-eslintrc.js/master/dot-eslintrc.js > .eslintrc.js
```

This downloads the configuration file into the current directory, creating or overwriting `.eslintrc.js` — ESLint relies on this filename. Assuming your project already uses ESLint, all you need to do is invoke ESLint going forwards with the `--fix` command. I myself use [ESLint-Formatter](https://github.com/TheSavior/ESLint-Formatter) with Sublime Text 3 to invoke ESLint with a shortcut: `⇧⌘3`.
