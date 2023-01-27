# rust-nightly-template
Rust nightly template x86_64-unknown-linux-musl

## To get started:
* **Download the latest revision**
```
git clone https://github.com/VHSgunzo/rust-nightly-template.git && cd rust-nightly-template
```
* **Compile a binary**
```
rustup default nightly
rustup target add x86_64-unknown-linux-musl
rustup component add rust-src --toolchain nightly
cargo build --release
```
* Or take an already precompiled binary file from the [releases](https://github.com/VHSgunzo/rust-nightly-template/releases)

* **Usage**
```
./template {args}
```
