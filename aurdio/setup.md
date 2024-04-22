//https://blog.logrocket.com/complete-guide-running-rust-arduino/

Run this commands
rustup toolchain install nightly
sudo apt install avr-libc gcc-avr pkg-config avrdude libudev-dev build-essential
sudo apt update 
sudo apt upgrade
cargo +stable install ravedude