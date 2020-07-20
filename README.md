<!--
  -- Copyright 2020 Contributors to the Parsec project. 
  -- SPDX-License-Identifier: Apache-2.0
--->
# PSA Cryptography API Rust Wrapper

<p align="center">
  <a href="https://github.com/parallaxsecond/rust-psa-crypto/actions?query=workflow%3A%22Continuous+Integration%22"><img src="https://github.com/parallaxsecond/rust-psa-crypto/workflows/Continuous%20Integration/badge.svg" alt="CI tests"/></a>
  <a href="https://travis-ci.com/parallaxsecond/rust-psa-crypto"><img src="https://travis-ci.com/parallaxsecond/rust-psa-crypto.svg?branch=master" alt="Travis CI tests"/></a>
</p>

This repository contains a Rust wrapper around the [PSA Cryptography API](https://developer.arm.com/architectures/security-architectures/platform-security-architecture/documentation). There are two layers of wrapping:

* [`psa-crypto-sys`](psa-crypto-sys): a lower-level wrapper that exposes a minimal low-level C interface to Rust

* [`psa-crypto`](psa-crypto): a higher-level, more Rust-friendly interface

## Notice

The PSA Crypto wrapper is currently work-in-progress. This repository is currently mainly a space for prototyping and design discussion.

## License

The software is provided under Apache-2.0. Contributions to this project are accepted under the same license.

This project uses the following third party crates:

* bingden (BSD-3-Clause)
* cmake (MIT and Apache-2.0)
* cc (MIT and Apache-2.0)
* log (MIT and Apache-2.0)
* serde (MIT and Apache-2.0)
* walkdir (MIT or UNLICENSE)

## Contributing

Please check the [**Contribution Guidelines**](https://parallaxsecond.github.io/parsec-book/contributing.html)
to know more about the contribution process.
