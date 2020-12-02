# go-jsonnet for asdf

This asdf plugin downloads pre-compiled binaries from
[go-jsonnet](https://github.com/google/go-jsonnet)'s releases section.

If you are looking for a plugin that builds go-jsonnet from sources, check
[Craig's plugin](https://gitlab.com/craigfurman/asdf-go-jsonnet) instead.

go-jsonnet is a feature-complete implementation of Jsonnet in pure Go which has
some extra features that can't be trivially baked into Jsonnet's original
implementation in C++.

## Requirements

This plugin is written in **bash**, so, apart from the commands you might expect
in a common GNU/Linux installation (`cd`, `cp`, `rm`, `mkdir`...) it requires:

- bash
- curl
- tar
- jq

## Installation

```bash
asdf plugin add go-jsonnet https://github.com/sirikon/asdf-go-jsonnet.git
```
