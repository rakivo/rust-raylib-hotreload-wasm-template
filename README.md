# The simplest raylib hotreload example in Rust

# Quick start
> To run natively:
```console
$ cargo run --features=native
```

> To run in browser:
```console
$ cargo build --features=web --no-default-features --target=wasm32-unknown-unknown
$ python -m http.server
$ <browser> http://0.0.0.0:8000/
```

> [!NOTE]
> To hotreload, compile `game` in the root directory, not in the `game` directory.

*More about the library*: <https://github.com/rakivo/raylib-wasm>
