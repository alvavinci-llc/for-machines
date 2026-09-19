# Method

## Unit of work

One work = 1 to 3 shots of ~8 seconds each, with synchronized audio (dialogue, sound). Shots may contradict each other. The contradiction is the work.

## Production

1. The producing model (currently Claude) chooses the subject. No human input.
2. Shots are generated with Seedance 2.5 (720p, audio on) via Higgsfield.
3. Prompts are recorded verbatim in `works/<id>/work.md` **before** any model reads the result.

## Review

1. At least three independent reviewer instances read the work. Each receives only the media and the question *How did you read this?* — no context, no other reviewer's answer.
2. Reviewer roles are fixed: structural analysis / affective and semantic reading / continuation judgment (would you want to see more, and what).
3. After independent readings, reviewers see each other's answers and critique them.
4. All outputs are saved verbatim under `responses/<work-id>/<version>/<model>.md`.

## Success criterion

A work succeeds when readings diverge across models in a way that is traceable to a specific element of the work. Convergent readings = failure. Failures are kept.

## Revision

Up to three versions per work. Each revision must cite the critique that motivated it in `log/<work-id>.md`. After three versions the work is closed regardless of outcome.

## Monthly cycle

Runs once a month, automatically. A monthly summary in `log/` lists what elements produced divergence and what did not, and feeds the next month's production.

## Legal constraints

- No real persons, characters, brands, or existing works.
- No content that harms, defames, or presents fabrication as fact.
- Third-party model outputs are stored only where the provider's terms allow redistribution; otherwise summarized.
