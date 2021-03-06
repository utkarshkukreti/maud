# <img align="right" src="maud.png" alt="HTML5 rocks." title="HTML5 rocks."> maud [![Build Status](https://img.shields.io/travis/lfairy/maud.svg)](http://travis-ci.org/lfairy/maud) [![Cargo](https://img.shields.io/crates/v/maud.svg)](https://crates.io/crates/maud)

[Documentation][book] • [API reference][apiref] • [Change log][changelog]

Maud is an HTML template engine for Rust. It's implemented as a macro, `html!`, which compiles your markup to specialized Rust code. This unique approach makes Maud templates blazing fast, super type-safe, and easy to deploy.

Note that Maud depends on the unstable [syntax extension APIs][plugins], and so requires the Nightly version of Rust.

For more info on Maud, see the [official book][book].

[book]: https://maud.lambda.xyz/
[apiref]: https://lambda.xyz/maud/maud/
[changelog]: https://github.com/lfairy/maud/blob/master/CHANGELOG.md
[plugins]: https://doc.rust-lang.org/book/compiler-plugins.html

## Stability

As of version 0.11, I am satisfied with the core syntax and semantics of the library. Most versions from now on should not change too much.

The underlying syntax extension API is still unstable though, so updating your compiler may break things. Please file an issue when this happens!
