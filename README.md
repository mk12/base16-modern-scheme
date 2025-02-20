# Base16 Modern Scheme

[Base16][] color schemes based on "Light Modern" and "Dark Modern" from VS Code.

## Usage

To build templates using this scheme:

```
pip3 install pybase16-builder
cd some/empty/directory
pybase16 update
git clone https://github.com/mk12/base16-modern-scheme schemes/modern
# Build all templates and schemes:
pybase16 build
# Build just modern:
pybase16 build -s 'modern-*'
```

Since I only use Base16 for [kitty][], I use a [custom build setup][b16kitty] that makes the process much easier.

[Base16]: https://github.com/chriskempson/base16
[kitty]: https://sw.kovidgoyal.net/kitty
[b16kitty]: https://github.com/mk12/base16-kitty/
