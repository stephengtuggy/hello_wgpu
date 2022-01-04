# hello_wgpu

My first Rust graphical program, using Wgpu.

## To build and run:

1. Set up Rust using the following:

```bash
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source $HOME/.cargo/env
rustc --version
```

2. `cd` to the hello_wgpu root directory, then run:

```bash
cargo build
cargo install --path .
```

3. Run it:

```bash
hello_wgpu
```
