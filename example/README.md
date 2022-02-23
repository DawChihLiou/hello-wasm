# hello-wasm Demo

## Getting Started

Make sure you linked the wasm package in the `/pkg` directory.

```bash
cd ../pkg && yarn link
```

Then in `/example` directory, run

```bash
yarn link hello-wasm
```

Now you are ready to install the dependencies.

```bash
yarn
```

After installation, run

```bash
# start dev server
yarn serve
```

By default, the site will be available at `http://localhost:8080`.
You'll see your WebAssembly in action!
