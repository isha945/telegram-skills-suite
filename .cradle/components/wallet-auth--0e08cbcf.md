# Wallet Auth

| Field | Value |
|-------|-------|
| Type | `wallet-auth` |
| ID | `0e08cbcf` |
| Category | app |
| Tags | auth, wallet, siwe, login, web3 |
| Description | WalletConnect, social login, SIWE |

## Configuration

| Setting | Value |
|---------|-------|
| Provider | rainbowkit |
| Wallet Connect Enabled | Enabled |
| Siwe Enabled | Enabled |
| Social Logins | (none) |
| Session Persistence | Enabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID` | WalletConnect Cloud project ID | Yes | No |  |
| `NEXT_PUBLIC_APP_NAME` | Application name for wallet dialogs | No | No | My DApp |

## Scripts

| Name | Command |
|------|---------|
| `wallet:setup` | `echo "Get your WalletConnect Project ID from https://dashboard.reown.com"` |

## Integration Points

**Depends on:**
- Erc8004-agent-runtime (`f6c87779`)
- X402-paywall-api (`a9607aeb`)
- Stylus-rust-contract (`16583eb3`)

