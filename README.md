# wasm-workspace

Simple proof-of-concept for a wgpu app using winit that can build on web (using webgl) or native window. Uses https://github.com/rukai/cargo-run-wasm and https://github.com/gfx-rs/wgpu/tree/master/wgpu/examples/hello-triangle.

On web: `cargo run-wasm hello-triangle`.
Native window: `cargo run --bin hello-triangle`.
