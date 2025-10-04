# eBPF Packet Drop Demo

This repository contains eBPF programs to drop TCP packets based on:

1. **Port number** (default 4040)
2. **Process name + port number** (default 4040 for a specific process)

## Requirements

- Linux kernel >= 5.3
- clang, llvm
- libbpf
- iproute2 (for XDP / tc)
- sudo/root privileges

## Build

```bash
make all
