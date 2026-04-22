# Constitution

Version: 1.0.0

## Purpose

Exercise the coordinator human-gate flow on a disposable repository.

## Principles

- Keep the repository intentionally minimal.
- Prefer deterministic coordinator behavior over product depth.

## Boundaries

- No real product development is expected here.
- This repository exists only for smoke-testing coordinator milestones.

## Quality Standards

- Human-gate smoke runs should be easy to inspect and easy to clean up.

## Stack

- language: typescript
- package_manager: pnpm
- install: pnpm install --frozen-lockfile
- test: pnpm test
- build: pnpm build

## Roadmap

### MVP
- Confirm the coordinator can pause for a human validation gate.

### Hardening
- Confirm the coordinator can resume after human acknowledgement.
