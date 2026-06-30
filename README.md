# FusionLayer Client (fxl)

[FusionLayer](https://fusionlayer.org/) is a GPU-powered EVM-compatible Layer 1 blockchain designed for decentralized applications and future appchain ecosystems.

The network is secured by **FusionHash**, a GPU-focused Proof-of-Work algorithm derived from CryptoNight-GPU and designed to promote broad miner participation through increased resistance to ASIC and FPGA specialization.

**fusionlayer-go (fxl)** is the official Golang implementation of the FusionLayer protocol, developed from the battle-tested codebase of [go-ethereum](https://github.com/ethereum/go-ethereum).

---

## Network Information

| Parameter | Value |
|------------|---------|
| Network Name | FusionLayer |
| Chain ID | 5070 |
| Currency Symbol | FXL |
| Consensus | FusionHash (Proof-of-Work) |
| Block Time | ~5 Seconds |

---

## Features

- 400+ TPS
- EVM Compatible
- GPU-Powered Proof-of-Work
- FusionHash Mining Algorithm
- Increased ASIC & FPGA Resistance
- High Performance Networking

---

## Download

Prebuilt binaries are available on the [Releases](https://github.com/0xFusionLayer/fusionlayer-go/releases) page.

---

## Building From Source

### Requirements

- Go 1.19 or later
- GCC / Clang or another C compiler
- Git

For general Go-Ethereum build requirements, see:

https://geth.ethereum.org/docs/getting-started/installing-geth

### Build

```bash
make fxl
```

After compilation, the executable will be located in:

```text
build/bin/fxl
```

---

## Running FusionLayer

Start a node:

```bash
./fxl
```

Display available options:

```bash
./fxl --help
```

For advanced node configuration, networking, RPC, account management, and developer tooling, many command-line options remain compatible with the upstream Geth implementation.

---

## FusionHash

FusionHash is the native Proof-of-Work algorithm of FusionLayer.

The algorithm is derived from CryptoNight-GPU and combines memory-hard computation with data-dependent memory access patterns designed to favor general-purpose GPUs while increasing the complexity of ASIC and FPGA development.

Design goals:

- GPU-First Mining
- Broad Hardware Accessibility
- Decentralized Hashrate Distribution
- Increased ASIC Resistance
- Increased FPGA Resistance
- Long-Term Network Security

Learn more:

https://github.com/0xFusionLayer/fusionhash-go

---

## Related Projects

### FusionHash

GPU-focused Proof-of-Work algorithm:

https://github.com/0xFusionLayer/fusionhash-go

### WarpMiner

Official GPU miner for FusionLayer:

https://github.com/0xFusionLayer/warpminer

---

## Contributing

Contributions are welcome.

To contribute:

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a pull request

Please ensure:

- Code is formatted using `gofmt`
- New code includes appropriate documentation
- Pull requests target the `main` branch
- Commit messages clearly describe the changes

Example:

```text
consensus: improve fusionhash verification performance
```

---

## License

### Libraries

All code outside the `cmd` directory is licensed under:

GNU Lesser General Public License v3.0 (LGPL-3.0)

See:

```text
COPYING.LESSER
```

### Executables

All code inside the `cmd` directory is licensed under:

GNU General Public License v3.0 (GPL-3.0)

See:

```text
COPYING
```

---

## Links

Website:
https://fusionlayer.org

