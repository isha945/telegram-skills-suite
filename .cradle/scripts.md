# Scripts

| Name | Command | Description |
|------|---------|-------------|
| `agent:start` | `tsx src/agent/runtime.ts` | Start the agent runtime |
| `agent:register` | `tsx src/agent/registry.ts register` | Register agent on-chain |
| `agent:status` | `tsx src/agent/registry.ts status` | Check agent registry status |
| `dev:api` | `tsx watch src/api/payments/server.ts` | Start payment API in dev mode |
| `build:api` | `tsc -p tsconfig.api.json` | Build payment API |
| `stylus:build` | `cd contracts/mycontract && cargo build --release --target wasm32-unknown-unknown` |  |
| `stylus:check` | `cd contracts/mycontract && cargo stylus check` |  |
| `deploy:sepolia` | `bash scripts/deploy-sepolia.sh` |  |
| `deploy:mainnet` | `bash scripts/deploy-mainnet.sh` |  |
| `deploy:sepolia` | `bash scripts/deploy-sepolia.sh` |  |
| `deploy:mainnet` | `bash scripts/deploy-mainnet.sh` |  |
| `fix-scripts` | `command -v dos2unix >/dev/null && dos2unix scripts/*.sh 2>/dev/null || echo "Run: dos2unix scripts/*.sh (install with: apt install dos2unix / brew install dos2unix)"` |  |
| `security:install` | `bash scripts/install-radar.sh` |  |
| `security:analyze` | `bash scripts/run-radar.sh` |  |
| `deploy:sepolia` | `bash scripts/deploy-sepolia.sh` |  |
| `deploy:mainnet` | `bash scripts/deploy-mainnet.sh` |  |
| `fix-scripts` | `command -v dos2unix >/dev/null && dos2unix scripts/*.sh 2>/dev/null || echo "Run: dos2unix scripts/*.sh (install: apt install dos2unix / brew install dos2unix)"` |  |
| `wallet:setup` | `echo "Get your WalletConnect Project ID from https://dashboard.reown.com"` | Instructions for wallet setup |
| `dev` | `next dev` | Start development server |
| `build` | `next build` | Build for production |
| `start` | `next start` | Start production server |
| `lint` | `next lint` | Run ESLint |
