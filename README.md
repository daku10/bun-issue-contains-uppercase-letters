# bun-issue-contains-uppercase-letters

## Prerequisites
- case-sensitive Filesystem
- Bun version: 1.2.23
- pnpm version: 10.17.1

## Commands

```bash
# failed
bun run --filter './packages/*' echo

# pnpm works
pnpm run --filter './packages/*' echo
```

