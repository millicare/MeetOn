# MeetOn

#Pre-install wasm compiler
rustup target add wasm32-unknown-unknown

#Create library crate
cargo new --lib ***

#Build out smart contract
cargo build --release --target wasm32-unknown-unknown
