# krb5-rs

This is a thin Rust wrapper around the [MIT krb5](https://web.mit.edu/kerberos/) library.

## State

The `krb5` crate is currently very incomplete; it is used in production by Stackable, but currently only exposes the functions that we use internally.

## Crates

* `krb5-sys` - Unsafe bindings generated automatically from the C headers
* `krb5` - Safe wrapper around `krb5-sys`
