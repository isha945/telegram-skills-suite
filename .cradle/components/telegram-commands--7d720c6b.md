# Commands

| Field | Value |
|-------|-------|
| Type | `telegram-commands` |
| ID | `7d720c6b` |
| Category | telegram |
| Tags | telegram, commands, bot, webhook |
| Description | Handle interactive commands via webhooks |

## Configuration

| Setting | Value |
|---------|-------|
| Commands | start, help, balance |
| Framework | grammy |
| Delivery Method | webhook |
| Rate Limit Enabled | Enabled |
| Chat Flow Enabled | Disabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `TELEGRAM_WEBHOOK_SECRET` | Secret for webhook verification | Yes | Yes |  |
| `TELEGRAM_BOT_TOKEN` | Bot token from @BotFather | Yes | Yes |  |

## File Structure

This component would generate the following files:

- `bot-client.ts` (backend-lib)
- `commands-composer.ts` (backend-lib)
- `telegram-webhook-route.ts` (backend-routes)

## Integration Points

**Depends on:**
- Erc8004-agent-runtime (`f6c87779`)

