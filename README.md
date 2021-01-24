# tfvm
A simple terraform version manager for Linux.

All bash. Does not required elivated privileges. Just make sure `$HOME/bin` is on your path.

### Install

Run this in the terminal:

```
curl https://raw.githubusercontent.com/aldiamond/tfvm/main/setup | sh
```

### Usage

```
>tfvm --help

Simple Linux terraform version manager.
 
Usage:
    tfvm version                display current running version of terraform
    tfvm list                   list installed versions of terraform
    tfvm install {{version}}    install terraform version
    tfvm set {{version}}        set terraform version
```
