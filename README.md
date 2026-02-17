# MiguelRodo's Homebrew Tap

This repository is a custom [Homebrew](https://brew.sh/) Tap for installing my personal tools and scripts on macOS.

## Included Formulae

* **repos** - A CLI tool to manage, clone, and setup git repositories.

## Installation

You can install the tools by tapping this repository and then installing the specific package.

### 1. Add this Tap
Register this repository with your Homebrew installation:

```bash
brew tap MiguelRodo/repos
```

### 2. Install Tools

You can now install the tools directly:

```bash
brew install repos
```

*Note: This will automatically install required dependencies (like `jq`).*

## Updating

To get the latest versions of the tools, simply run standard Homebrew updates:

```bash
brew update
brew upgrade repos
```

## Issues & Contributing

If you encounter issues with the installation (the formula), please open an issue in this repository.
For issues with the tool logic itself, please open an issue in the [source repository](https://github.com/MiguelRodo/repos).
