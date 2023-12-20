## Small C v1.1 for the Motorola 6x09 processor

Small C v1.1-to-pseudocode compiler.

### Status

Currently this compiles under 64-bit debian 11 (with a huge number of warnings). This version cannot compile this under Flex. If done correctly it is possible to use with Motorola 6x09 boards with no OS.

Interesting note, this compiler outputs psuedo code which gets assembled with an interpreter in assembler code appropriate to the processor. Currently there exists `run1.c` (6801/6803) and `run9.c` (6809). This repository has a lack of the documention on how the pseudocode functions. It is _an interesting approach_ that would be rather useful on the 6309 code plan.
