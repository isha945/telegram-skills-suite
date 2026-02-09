# Wallet Link

| Field | Value |
|-------|-------|
| Type | `telegram-wallet-link` |
| ID | `0f18fc06` |
| Category | telegram |
| Tags | telegram, wallet, link, verification |
| Description | Link Telegram profiles with Web3 wallets |

## Configuration

| Setting | Value |
|---------|-------|
| Verification Method | signature |
| Multi Wallet | Disabled |

## Environment Variables

| Key | Description | Required | Secret | Default |
|-----|-------------|----------|--------|---------|
| `NEXT_PUBLIC_TELEGRAM_BOT_USERNAME` | Your bot username (without @) | Yes | No |  |

## File Structure

This component would generate the following files:

- `link-service.ts` (backend-lib)
- `TelegramLinkButton.tsx` (frontend-components)
- `useTelegramLink.ts` (frontend-hooks)

## Integration Points

**Depends on:**
- Telegram-ai-agent (`4e67462e`)

