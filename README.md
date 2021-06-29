# spidev-test

from kernel.org[1]

[1] https://git.kernel.org/pub/scm/linux/kernel/git/torvalds/linux.git/tree/tools/spi?h=v5.13

For the loopback tests you might want to short-circuit the SPI bus MISO and MOSI lines.
A loopback enables the bus to receive the same data it is sending for basic and performance tests.

attempt to build quick and dirty yocto recipe for it
