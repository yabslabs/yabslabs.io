# yabslabs.io

## Introduction

This project automatily renders a `Github Page` and is available under https://yabslabs.io

## Prerequisit

### Install Hugo 

```Shell
brew install hugo
```

### Clone this Repo

The `Hugo` Themes are a git submodule.

To Clone just use:

```Shell
git clone --recursive https://github.com/yabslabs/yabslabs.io
```

## Run hugo

```Shell
cd docs
hugo server
```

This should start a server under http://localhost:1313/docs

## Edit content

Go to the `content` folder and simply edit the markdown files.
Push the changes to a `feature branch` and merge them into the `master`.

## Edit config

The `Hugo` config is the config.toml file in the project root.