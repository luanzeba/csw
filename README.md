# Codespace CLI Wrapper

Wrapper around the [`gh codespace`](https://cli.github.com/manual/gh_codespace) CLI.

Useful when working with multiple codespaces. 

It keeps track of the current codespace and automatically appends the `-c <codespace_name>` argument to your commands.

Inspired by [`kns`](https://github.com/blendle/kns) ❤️

## Usage
`csw` let's you select the working codespace.

`csw <command>` will forward the command to `gh codespace` with the codespace automatically appended. Works with [all `gh codespace` commands](https://cli.github.com/manual/gh_codespace).

When you use `csw` to create a codespace, it automatically sets it as the working codespace.

https://user-images.githubusercontent.com/20481048/160717251-b307d2c0-55ab-44b1-8617-c288ed4c4b89.mp4

## Dependencies
[`fzf`](https://github.com/junegunn/fzf)

[`gh` cli](https://cli.github.com/manual/installation)

## Installation
Put the **csw** file in a directory included in the `$PATH` environment variable and give the execution permission to the file.
```bash
curl https://raw.githubusercontent.com/luanzeba/csw/main/bin/csw -o path/to/file && chmod +x path/to/file
```

## Disclaimer
This is a work in progress. Contributions are welcome!

I realize that using `csw` instead of `gh codespace` isn't great. In and ideal scenario, the [gh cli config](https://cli.github.com/manual/gh_config) could support a setting for a working codespace and this wrapper could be replaced with an extension instead.
