## Minimal uaVM

**uaVM is a universal account virtual machine that solves the ethereum fragmentation problem at the account level. This is an attempt to build a minimal proof of concept using the Aligned Layer for proof aggregation and settlement on the Ethereum holesky testnet network.**

**Proofs are written in Rust and are generated using the SP1 zkVM by succint labs.**

Minimal uaVM consists of:

-   **Foundry**: The blazing fast ethereum testing framework.

## Documentation


## Usage

### Build

```shell
$ forge build
```

### Test

```shell
$ forge test
```

### Format

```shell
$ forge fmt
```

### Gas Snapshots

```shell
$ forge snapshot
```

### Anvil

```shell
$ anvil
```

### Deploy

```shell
$ forge script script/Counter.s.sol:CounterScript --rpc-url <your_rpc_url> --private-key <your_private_key>
```

### Cast

```shell
$ cast <subcommand>
```

### Help

```shell
$ forge --help
$ anvil --help
$ cast --help
```
