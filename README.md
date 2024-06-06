# IOAM Integrity: Linux kernel implementation

Based on the IETF draft [Integrity of In-situ OAM Data Fields](https://datatracker.ietf.org/doc/draft-ietf-ippm-ioam-data-integrity/), this repository proposes two different implementations in the Linux kernel:
 - [Option 2](./integrity_option2.patch)
 - [Option 3](./integrity_option3.patch)

Options 2 and 3 are explained (as well as other possibilities) in [these slides presented during IETF 119](https://datatracker.ietf.org/meeting/119/materials/slides-119-ippm-integrity-of-in-situ-oam-data-fields).

Note: both patches were created on top of net-next-6.8.0-rc6+.
