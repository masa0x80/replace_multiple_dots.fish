# replace_multiple_dots.fish

[![MIT LICENSE](http://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](LICENSE)

## Overview

This fish plugin converts `...` to `../..`.

## Installation

With [fresco]
```
$ fresco masa0x80/replace_multiple_dots.fish
```

With [fisherman]
```
$ fisher masa0x80/replace_multiple_dots.fish
```

## Usage

```
$ cd ...   # => cd ../..
$ cd ....  # => cd ../../..
```

## Authors

- ryotako
- Kimura Masayuki (masa0x80)

## References

- [fishでもdotを打った分だけ上の階層に行く方法](http://qiita.com/ryotako/items/68c003afa365f84fe100)
- [momo-lab/zsh-replace-multiple-dots](http://motemen.hatenablog.com/entry/2015/07/mackerel-mkr-peco-zsh)

[fresco]: https://github.com/masa0x80/fresco
[fisherman]: https://github.com/fisherman/fisherman
