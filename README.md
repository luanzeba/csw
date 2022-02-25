# Codespace Helper

Wrapper around the [`gh codespace`](https://cli.github.com/manual/gh_codespace) CLI.

Meant to help when working with multiple codespaces. 

It keeps track of the current codespace and automatically appends the `-c <codespace_name>` argument to your commands.

Inspired by [`kns`](https://github.com/blendle/kns) ❤️

## Usage
`csh` will use `fzf` to select the working codespace.

`csh dev` will create a codespace and ssh into it.

`csh <command>` works with all comands from `gh codespace`.

## Disclaimer
This is a work in progress.
