# Rust Hypervisor

# Useage

```shell
cargo build --release
codesign -s - --entitlements app.entitlements --force ./target/release/rust-hypervisor
./target/release/rust-hypervisor
```
