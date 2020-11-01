[![Build Status](https://dev.azure.com/mimblewimble/grin/_apis/build/status/mimblewimble.grin?branchName=master)](https://dev.azure.com/mimblewimble/grin/_build/latest?definitionId=1&branchName=master)
[![Coverage Status](https://img.shields.io/codecov/c/github/mimblewimble/grin/master.svg)](https://codecov.io/gh/mimblewimble/grin)
[![Chat](https://img.shields.io/gitter/room/grin_community/Lobby.svg)](https://gitter.im/grin_community/Lobby)
[![Support](https://img.shields.io/badge/support-on%20gitter-brightgreen.svg)](https://gitter.im/grin_community/support)
[![Documentation Wiki](https://img.shields.io/badge/doc-wiki-blue.svg)](https://github.com/mimblewimble/docs/wiki)
[![Release Version](https://img.shields.io/github/release/mimblewimble/grin.svg)](https://github.com/mimblewimble/grin/releases)
[![License](https://img.shields.io/github/license/mimblewimble/grin.svg)](https://github.com/mimblewimble/grin/blob/master/LICENSE)

# MWC

MWC is an in-progress implementation of the MimbleWimble protocol. Many characteristics are still undefined but the following constitutes a first set of choices:

  * Clean and minimal implementation, and aiming to stay as such.
  * Follows the Mimblewimble protocol, which provides hidden amounts and scaling advantages.
  * Cuckoo Cycle proof of work in two variants named Cuckaroo (ASIC-resistant) and Cuckatoo (ASIC-targeted).
  * Relatively fast block time: one minute.
  * Fixed block reward over time with a decreasing dilution.
  * Transaction fees are based on the number of Outputs created/destroyed and total transaction size.
  * Smooth curve for difficulty adjustments.

To learn more, read our [introduction to MimbleWimble](doc/intro.md).

## Status

Much is left to be done and [contributions](CONTRIBUTING.md) are welcome (see below).

## Contributing

To get involved, you can read our [contributing docs](CONTRIBUTING.md).

## Getting Started

To learn more about the technology, read our [introduction](doc/intro.md).


To build and try out MWC, see the [build docs](doc/build.md).

## Credits

Tom Elvis Jedusor for the first formulation of MimbleWimble.

Andrew Poelstra for his related work and improvements.

John Tromp for the Cuckoo Cycle proof of work.

## License

Apache License v2.0.

