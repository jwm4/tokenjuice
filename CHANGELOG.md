# Changelog

## Unreleased

### Fixes

- Route `node scripts/run-vitest.mjs` output through the Vitest reducer so Rolldown plugin-timing warnings do not drown out passing test summaries.
- Keep Tokenjuice's Codex hook compatible with current Codex hook and approval surfaces, including `hooks`, `PermissionRequest`, Windows commands, async hooks, and approval/sandbox doctor reporting.
