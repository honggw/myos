# Readme

## compilation

### 1
rustup target add thumbv7em-none-eabihf
cargo build --target thumbv7em-none-eabihf
### 2
cargo rustc -- -C link-args="/ENTRY:_start /SUBSYSTEM:console"
