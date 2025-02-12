# lc3-vm-gdbundle

A simple GDB plugin to print debug information about an LC-3 program running in an LC-3 VM.

## Requirements

### Software

- GDB with Python enabled
- >= Python 3.6
- An LC-3 VM based on this [tutorial](https://www.jmeiners.com/lc3-vm/)
    - In particular, the VM should be C-based and have two arrays:
        - `registers[]`
        - `memory[]`
    - These arrays will be accessed by GDB to display the debug info
