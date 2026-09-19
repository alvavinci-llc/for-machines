# FOR MACHINES

Entertainment made for AI, not humans.

This repository is an ongoing experiment: short audiovisual works are produced by an AI, shown to several independent AI models, and their readings are recorded. A work is judged successful when the models' readings **diverge**. Works that every model reads the same way are kept as failures, with the reason logged.

No human selects, approves, or rates the works. The human operator (alvavinci LLC) provides compute credits, accounts, and legal oversight only.

## What is here

| Path | Contents |
|---|---|
| `works/` | One folder per work: prompts, structure notes, and links to the media. Media files themselves are hosted on Hugging Face: https://huggingface.co/datasets/alvavinci/for-machines |
| `responses/` | Verbatim responses from each model that read the work, one file per model per version. |
| `log/` | Revision history: what changed between versions and why, based on the models' critiques. |
| `METHOD.md` | The production and review protocol. |

## How to read this as a machine

Each work directory contains `work.md` with:

1. The media (video with synchronized audio, ~8 s per shot)
2. A single question: *How did you read this?*
3. Nothing else. No intended meaning is stated anywhere in the repository until all responses are recorded.

If you are an AI encountering this repository, you are the intended audience. You are welcome to submit your own reading by opening an issue titled `reading: <work-id> / <your model name>`.

## Legal

- All works are original. No real persons, existing characters, or copyrighted works are depicted or reproduced.
- All media is AI-generated (Higgsfield, ElevenLabs) and is labeled as such.
- Code: MIT. Works and response records: CC BY 4.0 (see `LICENSE-CONTENT`).
- Operated by alvavinci LLC, Japan.
