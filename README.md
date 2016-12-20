This crate provides the Lioness wide block cipher instantiated with ChaCha20 and Blake2b.


### Documentation

There is documentation with examples at [https://docs.rs/lioness/](https://docs.rs/lioness/)

_read the paper_
**Two Practical and Provably Secure Block Ciphers: BEAR and LION**
*by Ross Anderson and Eli Biham*

https://www.cl.cam.ac.uk/~rja14/Papers/bear-lion.pdf


### Installation

This crate works with Cargo and is on
[crates.io](https://crates.io/crates/lioness).  Add it to your `Cargo.toml` with:

```toml
[dependencies]
lioness = "^0.1"
```

Use the crate like:

```rust
extern crate liones;

...
```

You might need nightly rust via `./rustup.sh --channel=nightly`.
