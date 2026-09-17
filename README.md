# vix-zed

Zed language support for [Vix](https://github.com/vixenware/vix-treesitter): syntax highlighting, brackets, and indentation for `.vix` files.

## Install (dev extension)

1. Clone this repository.
2. In Zed: `zed: install dev extension` and pick the clone.

Zed fetches and builds the grammar from `vix-treesitter` at the pinned `rev` in `extension.toml`; the tree-sitter CLI is not needed.

## Updating the grammar

The query files under `languages/vix/` are copied verbatim from `vix-treesitter/queries/`. After changing the grammar there, copy the queries here and bump `rev`.
