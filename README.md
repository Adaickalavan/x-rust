# x-rust

Install Rust by following instructions at https://www.rust-lang.org/tools/install or at https://rustup.rs/  .

Generate an executable binary using the Rust compiler rustc.
```bash
$ cd <working-directory>
# Generate binary
$ rustc main.rs
# Execute binary
$ ./main
# Check version of Rust compiler
$ rustc --version
# Update Rust installation
$ rustup update

# Build and run Rust file
$ cargo run

# Visualize the module tree of your project
$ cargo install cargo-modules
$ cargo-modules
```

Rust tutorial:
1. https://rust-exercises.com/100-exercises/

Code rules:
1. Avoid writing complex code. Write simple straightforward code.
1. No multilevel inheritance. Maximum inheritance of 1 level only.
1. No nested modules.