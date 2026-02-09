# ERC-8004 Agent

| Field | Value |
|-------|-------|
| Type | `erc8004-agent-runtime` |
| ID | `f6c87779` |
| Category | agents |
| Tags | ai, agent, erc8004, llm, registry |
| Description | AI agent with on-chain registry |

## Configuration

| Setting | Value |
|---------|-------|
| Agent Name | MyAgent |
| Agent Version | 0.1.0 |
| Capabilities | text-generation |
| Registry Integration | Enabled |
| Selected Model | openai/gpt-4o |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `AGENT_NAME` | Name of the AI agent | Yes | No | MyAgent |
| `OPENROUTER_API_KEY` | OpenRouter API key for LLM access | Yes | Yes |  |
| `OPENROUTER_MODEL` | Model to use via OpenRouter | No | No | openai/gpt-4o |
| `NEXT_PUBLIC_AGENT_REGISTRY_ADDRESS` | ERC-8004 registry contract address | No | No |  |
| `AGENT_PRIVATE_KEY` | Agent wallet private key for registry operations | No | Yes |  |
| `NEXT_PUBLIC_AGENT_NETWORK` | Network for agent operations (arbitrum or arbitrum-sepolia) | Yes | No | arbitrum |

## Scripts

| Name | Command |
|------|---------|
| `agent:start` | `tsx src/agent/runtime.ts` |
| `agent:register` | `tsx src/agent/registry.ts register` |
| `agent:status` | `tsx src/agent/registry.ts status` |

## Integration Points

**Provides to:**
- Telegram-ai-agent (`4e67462e`)
- Telegram-commands (`7d720c6b`)
- Telegram-notifications (`19750eca`)
- Wallet-auth (`0e08cbcf`)

