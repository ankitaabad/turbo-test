# AGENTS.md

## Do not commit

- **Turborepo remote cache configuration** — `TURBO_TOKEN`/`TURBO_TEAM` references in workflows and the `--remote-cache` flags are for CI-only usage. These changes reference secrets/vars that must be configured per-environment and should not be committed.
