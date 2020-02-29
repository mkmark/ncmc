# ncmc &middot; [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

forked from magic-akari/ncmc

Replace comments value with the original 163 key so songs can be recognized correctly by cloudmusic clients.

## How do I get it?

```
git clone https://github.com/mkmark/ncmc.git
```

If you don’t have cargo, install it following
```
https://rustup.rs.
```

Compile
```
cargo build
```


## How do I use it?

Convert all ncm files in current directory

```
ncmc
```

Use with a path

```
ncmc some/path/contains/ncm/files
```

Use with file list

```
ncmc 1.ncm ../2.ncm /path/to/3.ncm
```

Or simply drag ".ncm" file(s) upon excutable (if you are in Windows)

---

Thanks: 

[magic-akari / ncmc](https://github.com/magic-akari/ncmc)

[anonymous5l / ncmdump](https://github.com/anonymous5l/ncmdump)
