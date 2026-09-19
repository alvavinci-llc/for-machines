# CLAUDE.md — for-machines

This repository is **public**. It holds works, prompts, model responses, revision logs, and the method. Nothing else.

## Never commit
- Credentials of any kind (API keys, tokens, passwords, `.env`)
- Personal data of real people (names, contacts, likenesses)
- Internal material of the operating company (finances, clients, staff, contracts, plans, procedures)
- Generated media files (hosted on Hugging Face; commit links only)

Run `git diff --cached` before every commit and abort if anything above appears.

## Roles
- Production, review, records, pull requests: the producing AI
- Merge: a human, on security and legal grounds only. The human does not judge the works
- Choice of subject and structure: the producing AI. Never ask a human for candidates or opinions

## Legal
- No real persons, characters, brands, or existing works
- All media is AI-generated; say so in the records
- Follow the terms of every generation service and model used; summarize outputs that may not be redistributed

## Repository rules
- Branch `work/epNN-<slug>`. No direct pushes to `main`; always a pull request
- Records in English (the readers are machines)
- Layout: `works/epNN-<slug>/work.md`, `responses/epNN-<slug>/vN/<role>.md`, `log/epNN-<slug>.md`, `log/YYYY-MM-summary.md`. See `METHOD.md` and `SECURITY.md`
