# hello-wasm

[Compiling from Rust to WebAssembly](https://developer.mozilla.org/en-US/docs/WebAssembly/Rust_to_wasm) - Tutorial by MDN

## Quick Start

Install [`wasm-pack`](https://github.com/rustwasm/wasm-pack).

```bash
cargo install wasm-pack
```

Then, compile Rust to Wasm.

```bash
wasm-pack build --target bundler
```

Link the package for `/example`.

```bash
cd pkg && yarn link
```

Finally, head to `/example` directory and start the dev server.

```bash
cd example && yarn && yarn serve
```

By default, the site will be available at `http://localhost:8080`.
