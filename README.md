# Dotfiles

This config based on usage of the [Stow](#stow) to link config files to the needed places.

[Nix package manager and darwin-modules](#nix-packages) mostly used as package manager.

## How to clone

```sh
git clone --recurse-submodules https://github.com/MrRTi/dotfiles.git
cd dotfiles
```

```sh
git clone --recurse-submodules git@github.com:MrRTi/dotfiles.git
cd dotfiles
```

## Required

- [brew](https://brew.sh/)
- [GNU Stow](https://www.gnu.org/software/stow/) (included in Brewfile)

## Brew

### Requirements

- [brew](https://brew.sh/)

### Usage

#### Install brew (use command from original site)

```sh
./brew.sh -i
```

#### Install all packages listed in Brewfile (restore)

```sh
./brew.sh -r
```

#### Save list of installed packages in Brewfile

```sh
./brew.sh -d
```

#### Help

To see all possible options

```sh
./brew.sh -h
```
## Stow

### Requirements

- [GNU Stow](https://www.gnu.org/software/stow/)

### Usage

#### Add

For specific package

```sh
./stow.sh -a -p nvim
```

For all configs

```sh
./stow.sh -a
```

#### Delete

For specific package

```sh
./stow.sh -d -p nvim
```

For all configs

```sh
./stow.sh -d
```

#### Help

To see all possible options

```sh
./stow.sh -h
```


