# Using sourmash in other programming languages (via FFI)

The goal for this repo is to organize experiments around using sourmash in
other languages (beside the supported one, Python).

## First class support

- [sourmash core][0]: Rust
- [sourmash][1]: Python (using `milksnake` + `cffi` for interacting with core)

[0]: https://crates.io/crates/sourmash
[1]: https://pypi.org/project/sourmash/

## Prototypes and demos

- sourmash-r
- sourmash_cpp
- [sourmash][2]: wasm generated with wasm-pack (from core)

[2]: https://www.npmjs.com/package/sourmash

## Someday?

- node: neon?
    * better just to wait for wasm support?
- erlang: [rustler](https://github.com/rusterlium/rustler)
- ruby: helix
  - helix
  - [rutie](https://github.com/danielpclark/rutie) ([example](https://medium.com/swlh/speeding-up-ruby-mri-with-rust-a7c914d2f9d0))
- julia ([example][3])

[3]: https://github.com/felipenoris/JuliaPackageWithRustDep.jl
