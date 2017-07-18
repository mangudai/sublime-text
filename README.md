# AoE2 Random Map Scripting

> Age of Empires 2 Random Map Scripting support for Sublime Text

![Screeshot of syntax highlighting](https://github.com/mangudai/sublime-text/blob/master/screenshot.png?raw=true)

## Install

- Install [Package Control](https://packagecontrol.io/) for Sublime Text.
- Select `Install Package` in command palette, then search `aoe2-rms`.

## Release Notes

### 0.2.1, 0.2.2

- Allowed identifiers to start with digits.

### 0.2.0

- Separated VS Code and Sublime Text support into two repos as they're becoming quite different.
- Pulled latest changes from VS Code extension.

### 0.1.2

- Fixed highlighting of command blocks that start on the same line: `create_object TOWN_CENTER { ... }`.
- Fixed parsing `if` and `elseif` where identifier is valid but not UPPER_CASE. Identifiers can be almost anything.

### 0.1.1

- Fixed highlighting of inline comments after commands and directives.
- Added meta info: `LICENSE` file, links to the repo in `package.json`.

### 0.1.0

- Added syntax highlighting.
