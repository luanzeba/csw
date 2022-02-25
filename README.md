# Codespace CLI Wrapper

Wrapper around the [`gh codespace`](https://cli.github.com/manual/gh_codespace) CLI.

Meant to help when working with multiple codespaces. 

It keeps track of the current codespace and automatically appends the `-c <codespace_name>` argument to your commands.

Inspired by [`kns`](https://github.com/blendle/kns) ❤️

## Usage
`csw` will use `fzf` to select the working codespace.

`csw dev` will create a codespace and ssh into it.

`csw <command>` works with all comands from `gh codespace`.

## Installation
To install **csw** you can just run this command:
```bash
curl https://raw.githubusercontent.com/luanzeba/csw/main/bin/csw -o /usr/local/bin/csw && chmod +x $_
```

## Disclaimer
This is a work in progress.
