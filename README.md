# Multi-language programming playground

## Summary

Programming playground for:

- Go
- Python
- Rust
- TypeScript

Additional features:

- CI (GitHub Actions)
- Static code analysis: formatting and linting

## Setup

1. Clone repository with `git` and `cd` into cloned repo
2. Optional: install recommended software _(read below)_
3. Optional: install runtimes by running `asdf install`
4. Continue:
   - Go - [README](go/README.md)
   - Python - [README](python/README.md)
   - Rust - [README](rust/README.md)
   - TypeScript - [README](typescript/README.md)

## Recommended software

| Software                    | Description                          |
| :-------------------------- | :----------------------------------- |
| [asdf](https://asdf-vm.com) | Multiple runtime version manager     |
| [trunk](https://trunk.io)   | Developer experience (DevEx) toolkit |

### asdf

Defined runtimes:

| Runtime  | Version   | Repository                                    |
| :------- | :-------- | :-------------------------------------------- |
| `golang` | `1.22.1`  | https://github.com/kennyp/asdf-golang         |
| `python` | `3.12.2`  | https://github.com/asdf-community/asdf-python |
| `rust`   | `1.77.0`  | https://github.com/code-lever/asdf-rust       |
| `nodejs` | `20.11.1` | https://github.com/asdf-vm/asdf-nodejs        |

### Trunk

Useful commands:

| Command       | Description                                                           |
| :------------ | :-------------------------------------------------------------------- |
| `trunk fmt`   | Check files formatting with `Trunk` (by default, only modified files) |
| `trunk check` | Lint files with `Trunk` (by default, only modified files)             |
