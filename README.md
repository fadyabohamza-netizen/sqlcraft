# SQLCraft 🗄️

**Describe it. Get the SQL.** — Describe what you want in plain English, get SQL.

## What it does

Describe the query you want in plain English and SQLCraft writes clean SQL for your dialect. Powered by Pollinations.

- **Connect Pollen** → approve the consent screen → every request is paid from **your own** Pollen balance (default budget 5, valid 7 days, revocable anytime from https://enter.pollinations.ai/keys).
- Free tier: `openai/gpt-5.4-nano` · Premium toggle: `openai/gpt-5.5`.

## Options

- **Dialect:** `SQLite/PostgreSQL/MySQL/SQL Server`
## Stack

- Static single-file frontend (no build step), deployed on GitHub Pages.
- Pollinations [Connect User Wallets / BYOP](https://github.com/pollinations/pollinations/blob/main/BRING_YOUR_OWN_POLLEN.md) OAuth PKCE flow — the app never touches your secret key.
- Scoped keys live in `sessionStorage` only, never localStorage/logs/URLs.

## Links

- **Live app:** https://fadyabohamza-netizen.github.io/sqlcraft/
- Source: https://github.com/fadyabohamza-netizen/sqlcraft
- App key (publishable, earnings enabled): `pk_wn0RwwjY51ERmb9d`
- Powered by [Pollinations](https://gen.pollinations.ai) · Author: [fadyabohamza-netizen](https://github.com/fadyabohamza-netizen)
