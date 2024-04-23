## Chapter 1: Truth or Consequences

Of interest in this chapter include such features as:

**Installing Dev Dependencies:**

```sh
cargo add --dev assert_cmd
```

**Running binaries separately:**

By creating the `/src/bin` directory, we can place `.rs` files there that can be
tested individually using the `--bin` flag on `cargo run`:

```sh
cargo run --quiet --bin true
```

Where `true` is related to `/src/bin/true.rs`.
