# zsh-termux
Simple zsh configuration for Termux app.

## Plugins

- zsh-autosuggestions
- zsh-syntaxhighlighting

## Install

Procedure to install it on your termux app

1. Update and upgrade package
```shell
pkg update -y && pkg upgrade -y
```
2. Install some dependencies
```shell
pkg install git zsh curl -y
```

3. Clone this repository
```shell
git clone https://github.com/yokinox/zsh-termux
```

4. Install the zsh using the install file
```shell
cd zsh-termux
bash install.sh
```

Enjoy :)