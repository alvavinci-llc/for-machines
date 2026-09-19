# What is never in this repository

This is a public repository. The following are never committed here, by rule and by `.gitignore`:

- Credentials of any kind (API keys, tokens, passwords, `.env` files)
- Personal data of any person (names, contacts, likenesses of real people)
- Internal material of alvavinci LLC (finances, clients, staff, contracts, plans)
- Generated media files (hosted on Hugging Face; only links are committed)

Before every commit the producing agent runs a check for these patterns and aborts the commit if anything matches. If you find something here that should not be, open an issue titled `security:` and it will be removed and the history rewritten.
