# :rainbow: alacritty-themes :lollipop:

![Build and Deploy](https://github.com/rajasegar/alacritty-themes/workflows/Build%20and%20Deploy/badge.svg)
[![npm version](http://img.shields.io/npm/v/alacritty-themes.svg?style=flat)](https://npmjs.org/package/alacritty-themes "View this project on npm")
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg)](https://github.com/semantic-release/semantic-release)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

 Themes :candy: for [alacritty](https://github.com/alacritty/alacritty)  A cross-platform, GPU-accelerated terminal emulator 

To find the list of themes, you can visit the alacritty [wiki page](https://github.com/alacritty/alacritty/wiki/Color-schemes)

- Live preview the themes
- 150+ Themes to choose from
- Apply any theme with just one command at the terminal
- Option to create your `alacritty.yml` config file
- Simple, Easy and intuitive User experience

## Install

Install the `alacritty-themes` package globally with [npm](https://npmjs.com)
```
npm i -g alacritty-themes
```

If you are using `npx` you don't have to install the package:

```
npx alacritty-themes
```

If you are using Archlinux, you can install it from [AUR](https://aur.archlinux.org/packages/alacritty-themes/)

```
paru -S alacritty-themes
```

## Usage

```
alacritty-themes
```

To apply a theme directly, provide the theme name as an option
```
alacritty-themes Dracula
```

To find the themes, you can check the file names  [here](/themes)

![alacritty-themes demo gif](demo.gif)

Choose the theme from the list of options by typing the theme name and press `Enter` to apply.
The list of options are cycled through automatically so you can go to the last theme
by just pressing `up arrow` key.
The search is fuzzy so you can enter any part of the theme name to search.

If no `alacritty.yml` is found in your `$HOME` path, you can create one using the `--create` or `-c` option.

```
alacritty-themes --create
```

## Bonus Tip: Alias
You can also create an alias for `alacritty-themes` like `at` 
Just append this below line to your `~/.bashrc` or `~/.bash_profile`

```
alias at='alacritty-themes'
```

Now you can simply use `at` to choose themes for your alacritty terminal.

```
at
```
