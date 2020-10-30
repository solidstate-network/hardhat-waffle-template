# TODO

This repository was generated from a template or is the template itself.  For more information, see [docs/TEMPLATE.md](./docs/TEMPLATE.md).

## Development

Install dependencies via Yarn:

```bash
yarn install
```

Compile contracts via Hardhat:

```bash
yarn run hardhat compile
```

### Networks

By default, Hardhat uses the Hardhat Network in-process.

To use an external network via URL, set the `URL` environment variable and append commands with `--network generic`:

```bash
URL="https://mainnet.infura.io/v3/[INFURA_KEY]" yarn run hardhat test --network generic
```

### Testing

Test contracts via Hardhat:

```bash
yarn run hardhat test
```

Activate gas usage reporting by setting the `REPORT_GAS` environment variable to `"true"`:

```bash
REPORT_GAS=true yarn run hardhat test
```
