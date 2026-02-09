# SmartCache Caching

| Field | Value |
|-------|-------|
| Type | `smartcache-caching` |
| ID | `8d16aec4` |
| Category | contracts |
| Tags | cache, gas, optimization, stylus |
| Description | Enable contract caching for cheaper gas |

## Configuration

| Setting | Value |
|---------|-------|
| Crate Version | latest |
| Auto Opt In | Enabled |

## Scripts

| Name | Command |
|------|---------|
| `deploy:sepolia` | `bash scripts/deploy-sepolia.sh` |
| `deploy:mainnet` | `bash scripts/deploy-mainnet.sh` |
| `fix-scripts` | `command -v dos2unix >/dev/null && dos2unix scripts/*.sh 2>/dev/null || echo "Run: dos2unix scripts/*.sh (install with: apt install dos2unix / brew install dos2unix)"` |

## File Structure

This component would generate the following files:

- `contracts/mycontract/Cargo.toml`
- `contracts/mycontract/src/lib.rs`
- `contracts/cached-contract/Cargo.toml`
- `contracts/cached-contract/src/lib.rs`
- `docs/SMARTCACHE_INTEGRATION.md`
- `scripts/deploy-sepolia.sh`
- `scripts/deploy-mainnet.sh`

## Integration Points

**Depends on:**
- Stylus-rust-contract (`16583eb3`)

