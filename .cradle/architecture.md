# Architecture

## Dependency Graph

```mermaid
graph TD
  f6c87779["Erc8004-agent-runtime (erc8004-agent-runtime)"]
  a9607aeb["X402-paywall-api (x402-paywall-api)"]
  16583eb3["Stylus-rust-contract (stylus-rust-contract)"]
  4e67462e["Telegram-ai-agent (telegram-ai-agent)"]
  7d720c6b["Telegram-commands (telegram-commands)"]
  19750eca["Telegram-notifications (telegram-notifications)"]
  8d16aec4["Smartcache-caching (smartcache-caching)"]
  c9dd0db7["Auditware-analyzing (auditware-analyzing)"]
  0e08cbcf["Wallet-auth (wallet-auth)"]
  0f18fc06["Telegram-wallet-link (telegram-wallet-link)"]
  17c62909["Frontend-scaffold (frontend-scaffold)"]
  f6c87779 --> 4e67462e
  f6c87779 --> 7d720c6b
  f6c87779 --> 19750eca
  f6c87779 --> 0e08cbcf
  a9607aeb --> 0e08cbcf
  16583eb3 --> 8d16aec4
  16583eb3 --> c9dd0db7
  16583eb3 --> 0e08cbcf
  4e67462e --> 0f18fc06
  4e67462e --> 17c62909
```

## Execution / Implementation Order

1. **Erc8004-agent-runtime** (`f6c87779`)
2. **X402-paywall-api** (`a9607aeb`)
3. **Stylus-rust-contract** (`16583eb3`)
4. **Telegram-ai-agent** (`4e67462e`)
5. **Telegram-commands** (`7d720c6b`)
6. **Telegram-notifications** (`19750eca`)
7. **Smartcache-caching** (`8d16aec4`)
8. **Auditware-analyzing** (`c9dd0db7`)
9. **Wallet-auth** (`0e08cbcf`)
10. **Telegram-wallet-link** (`0f18fc06`)
11. **Frontend-scaffold** (`17c62909`)
