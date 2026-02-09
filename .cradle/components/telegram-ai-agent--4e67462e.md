# AI Agent

| Field | Value |
|-------|-------|
| Type | `telegram-ai-agent` |
| ID | `4e67462e` |
| Category | telegram |
| Tags | telegram, ai, bot, llm, conversational |
| Description | Conversational AI bot with LLM integration |

## Configuration

| Setting | Value |
|---------|-------|
| Model Provider | openai |
| Personality | helpful |
| Context Memory | Enabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `TELEGRAM_BOT_TOKEN` | Bot token from @BotFather | Yes | Yes |  |
| `OPENAI_API_KEY` | API key for OpenAI | Yes | Yes |  |

## File Structure

This component would generate the following files:

- `bot-client.ts` (backend-lib)
- `ai-service.ts` (backend-lib)
- `ai-agent-composer.ts` (backend-lib)
- `telegram-webhook-route.ts` (backend-routes)

## Integration Points

**Depends on:**
- Erc8004-agent-runtime (`f6c87779`)

**Provides to:**
- Telegram-wallet-link (`0f18fc06`)
- Frontend-scaffold (`17c62909`)

