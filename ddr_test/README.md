## DDR Test

Run a full 512MB read / write test of the DDR3 memory on the ECPIX-5 board.

Tests:
* All 512MB of memory is written, read back, and verified (twice)
* Patterns (incrementing patterns, all ones)

Not tested:
* Data mask (DM) pins.
* High speed PCB routing (tests are run @ 50MHz DDR clock)

### Output

LEDs:
* Blue = Test in progress
* Red = Failed
* Green = Pass