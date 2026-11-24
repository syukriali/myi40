# CLAUDE.md

Guidance for Claude Code in this repository. Keep this file short (under ~100 lines)
and update it as the project grows.

## Project
- What it is: _TODO: one or two sentences about the project._
- Stack: _TODO: language, framework, database._

## Commands
- Install: _TODO_
- Run / dev server: _TODO_
- Test: _TODO_
- Lint / format: _TODO_

## Structure
- _TODO: key folders and what lives in them._

## Conventions
- Make small, focused changes; don't refactor unrelated code.
- Run tests and lint before saying a task is done.
- Never commit secrets (`.env`, keys, credentials).
- _TODO: naming, style, and patterns to follow or avoid._

## When setting up the stack
Once the stack is chosen, add its test/lint commands to `permissions.allow` in
`.claude/settings.json` and add a PostToolUse hook that runs the formatter after edits.
