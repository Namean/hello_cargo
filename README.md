# The Rust Programming Language

[Hello, Cargo!](https://doc.rust-lang.org/book/ch01-03-hello-cargo.html)



### Cargo build: Creates a binary in target/debug/**

        Because the default build is a debug build,
        Cargo puts the binary ina directory named debug


### Cargo run: Builds on change, and runs project

        Using cargo run is more convenient than having to remember to run cargo
        build and tehn use the whole path to the binary, so most developers use
        cargo run.

### Cargo check: Checks code compiles, does not produce binary

        Why would you not want an executible? Often, cargo check
        is much faster than cargo build because it skips the step
        of producing an executible. If your ocontinually checking
        your work while writing the code, using cargo check will
        speed up the process of

[Cargo docs](https://doc.rust-lang.org/cargo/)
