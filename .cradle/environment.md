# Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `AGENT_NAME` | Name of the AI agent | Yes | No | MyAgent |
| `OPENROUTER_API_KEY` | OpenRouter API key for LLM access | Yes | Yes |  |
| `OPENROUTER_MODEL` | Model to use via OpenRouter | No | No | openai/gpt-4o |
| `NEXT_PUBLIC_AGENT_REGISTRY_ADDRESS` | ERC-8004 registry contract address | No | No |  |
| `AGENT_PRIVATE_KEY` | Agent wallet private key for registry operations | No | Yes |  |
| `NEXT_PUBLIC_AGENT_NETWORK` | Network for agent operations (arbitrum or arbitrum-sepolia) | Yes | No | arbitrum |
| `PAYMENT_RECEIVER_ADDRESS` | Ethereum address to receive payments | Yes | No |  |
| `PAYMENT_PRIVATE_KEY` | Private key for signing receipts | Yes | Yes |  |
| `STYLUS_RPC_URL` | Arbitrum RPC URL for deployment | Yes | No | https://sepolia-rollup.arbitrum.io/rpc |
| `DEPLOYER_PRIVATE_KEY` | Private key for deployment | Yes | Yes |  |
| `TELEGRAM_BOT_TOKEN` | Bot token from @BotFather | Yes | Yes |  |
| `OPENAI_API_KEY` | API key for OpenAI | Yes | Yes |  |
| `TELEGRAM_WEBHOOK_SECRET` | Secret for webhook verification | Yes | Yes |  |
| `NEXT_PUBLIC_WALLETCONNECT_PROJECT_ID` | WalletConnect Cloud project ID | Yes | No |  |
| `NEXT_PUBLIC_APP_NAME` | Application name for wallet dialogs | No | No | My DApp |
| `NEXT_PUBLIC_TELEGRAM_BOT_USERNAME` | Your bot username (without @) | Yes | No |  |
