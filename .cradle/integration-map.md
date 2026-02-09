# Integration Map

How components connect and what data flows between them.

### Erc8004-agent-runtime --> Telegram-ai-agent

- **Source**: Erc8004-agent-runtime (`f6c87779`)
  - Output ports: Agent Runtime (api)
- **Target**: Telegram-ai-agent (`4e67462e`)
  

### Erc8004-agent-runtime --> Telegram-commands

- **Source**: Erc8004-agent-runtime (`f6c87779`)
  - Output ports: Agent Runtime (api)
- **Target**: Telegram-commands (`7d720c6b`)
  

### Erc8004-agent-runtime --> Telegram-notifications

- **Source**: Erc8004-agent-runtime (`f6c87779`)
  - Output ports: Agent Runtime (api)
- **Target**: Telegram-notifications (`19750eca`)
  

### Erc8004-agent-runtime --> Wallet-auth

- **Source**: Erc8004-agent-runtime (`f6c87779`)
  - Output ports: Agent Runtime (api)
- **Target**: Wallet-auth (`0e08cbcf`)
  

### X402-paywall-api --> Wallet-auth

- **Source**: X402-paywall-api (`a9607aeb`)
  - Output ports: API Endpoint (api)
- **Target**: Wallet-auth (`0e08cbcf`)
  

### Stylus-rust-contract --> Smartcache-caching

- **Source**: Stylus-rust-contract (`16583eb3`)
  - Output ports: Contract Code (contract)
- **Target**: Smartcache-caching (`8d16aec4`)
  - Input ports: Contract Input (contract)

### Stylus-rust-contract --> Auditware-analyzing

- **Source**: Stylus-rust-contract (`16583eb3`)
  - Output ports: Contract Code (contract)
- **Target**: Auditware-analyzing (`c9dd0db7`)
  - Input ports: Contract Input (contract)

### Stylus-rust-contract --> Wallet-auth

- **Source**: Stylus-rust-contract (`16583eb3`)
  - Output ports: Contract Code (contract)
- **Target**: Wallet-auth (`0e08cbcf`)
  

### Telegram-ai-agent --> Telegram-wallet-link

- **Source**: Telegram-ai-agent (`4e67462e`)
  - Output ports: AI Response (any)
- **Target**: Telegram-wallet-link (`0f18fc06`)
  

### Telegram-ai-agent --> Frontend-scaffold

- **Source**: Telegram-ai-agent (`4e67462e`)
  - Output ports: AI Response (any)
- **Target**: Frontend-scaffold (`17c62909`)
  - Input ports: Contract ABI (contract), Network Config (config)
