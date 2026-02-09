# Stylus Rust Contract

| Field | Value |
|-------|-------|
| Type | `stylus-rust-contract` |
| ID | `16583eb3` |
| Category | contracts |
| Tags | rust, stylus, arbitrum, custom |
| Description | Build Rust smart contracts for Arbitrum |

## Configuration

| Setting | Value |
|---------|-------|
| Network | arbitrum-sepolia |
| Example Type | counter |
| Contract Name | MyContract |
| Contract Code |  |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `STYLUS_RPC_URL` | Arbitrum RPC URL for deployment | Yes | No | https://sepolia-rollup.arbitrum.io/rpc |
| `DEPLOYER_PRIVATE_KEY` | Private key for deployment | Yes | Yes |  |

## Scripts

| Name | Command |
|------|---------|
| `stylus:build` | `cd contracts/mycontract && cargo build --release --target wasm32-unknown-unknown` |
| `stylus:check` | `cd contracts/mycontract && cargo stylus check` |
| `deploy:sepolia` | `bash scripts/deploy-sepolia.sh` |
| `deploy:mainnet` | `bash scripts/deploy-mainnet.sh` |

## File Structure

This component would generate the following files:

- `contracts/mycontract/Cargo.toml`
- `contracts/mycontract/src/lib.rs`
- `contracts/mycontract/STYLUS_SETUP.md`
- `scripts/deploy-sepolia.sh`
- `scripts/deploy-mainnet.sh`

## Integration Points

**Provides to:**
- Smartcache-caching (`8d16aec4`)
- Auditware-analyzing (`c9dd0db7`)
- Wallet-auth (`0e08cbcf`)

