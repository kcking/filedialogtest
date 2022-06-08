# filedialogtest

Test cases for winit file dialogs (and fullscreen toggling). These are copy-pasta'd examples from libraries.

## Testing

Each file in `src/bin` is a separate test you can run with `cargo run --bin <filename>`

Each of these tests are using my winit fork. This can be verified by running `cargo tree -p winit -i` and seeing that there is only one version of `winit` present.

```
cargo tree -p winit -i
winit v0.26.1 (https://github.com/kcking/winit#01f013c6)
└── filedialogtest v0.1.0 (/Users/kevin/src/xr/filedialogtest)
```
