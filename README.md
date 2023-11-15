# Run-Avail-network-full-node-on-windows-OS
Download Ubuntu 
https://ubuntu.com/download/desktop



Open new Ubuntu terminal, the run the following command 


X1.** Install Rust**

sudo apt-get update
sudo apt install build-essential
sudo apt install --assume-yes git clang curl libssl-dev protobuf-compiler
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
source ~/.cargo/env
rustup default stable
rustup update
rustup update nightly
rustup target add wasm32-unknown-unknown --toolchain nightly


