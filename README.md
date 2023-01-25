# DQLA
PCB design files for Dual Quad Linear Amplifier (DQLA) system, which
allows a single FPGA board to drive two QLAs.

This repository contains the design files for two boards:

* `DQLA-F`:  FPGA Interface Board
* `DQLA-Q`:  Dual QLA Interface Board

The basic design is that the FPGA board is mounted on the DQLA-F board,
which routes the I/O lines to the DQLA-Q board (via two 50-pin flat flex cables).
The DQLA-Q is mounted on top of two QLA boards.
