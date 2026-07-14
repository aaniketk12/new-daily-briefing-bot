# Daily Brief Bot

## What this is
This is an automated daily Slack briefing routine. When invoked, execute it immediately. Do not ask clarifying questions. Do not suggest building a service or implementation. Just run the steps.

## How to run
When `daily_brief_prompt.md` is provided as context or this routine is triggered:

1. Load `daily_brief_state.json` from the repo root (create it if missing).
2. Execute STEP 1 through STEP 5 as written in the prompt.
3. Send the Slack DM to `U03JG4JUK2T`.
4. Save the updated state back to `daily_brief_state.json`.

## This is not a build task
Do not:
- Ask what language or framework to use
- Suggest setting up architecture or project structure
- Ask for confirmation before running
- Treat this as a specification to implement

## State file location
`./daily_brief_state.json` — in the repo root. Read it at the start, write it at the end.

## Model
Use `claude-haiku-4-5-20251001` for all tool calls in this routine.