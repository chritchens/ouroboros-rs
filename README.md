# Ouroboros-rs

[![MIT licensed](https://img.shields.io/badge/License-MIT-blue.svg)](./LICENSE-MIT)
[![Apache-2.0 licensed](https://img.shields.io/badge/License-Apache%202.0-orange.svg)](./LICENSE-APACHE)
[![](https://travis-ci.org/chritchens/ouroboros-rs.svg?branch=master)](https://travis-ci.org/chritchens/ouroboros-rs?branch=master)

A wrapper around the [Ouroboros](https://github.com/dstaesse/ouroboros) API. WIP

## Requirements

For installing Ouroboros and its required libraries, follow the instructions on the [website](https://ouroboros.rocks/docs/start). The wrapper has been tried with Ouroboros version 0.16.0.

## Building

To build, just type from your terminal

```sh

$ cargo build --all

```

The Ouroboros code is provided as a submodule and fetched and built if it is not already in path. The minimum required version is 0.16.0.

## License

This project is license under either of

* Apache License, Version 2.0, (LICENSE-APACHE or http://www.apache.org/licenses/LICENSE-2.0)
* MIT license (LICENSE-MIT or http://opensource.org/licenses/MIT)

at your option.

## Contributing

Unless you explicitly state otherwise, any contribution intentionally submitted for inclusion in ouroboros-rs by you, as defined in the Apache-2.0 license, shall be dual licensed as above, without any additional terms or conditions.
