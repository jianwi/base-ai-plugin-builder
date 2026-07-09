# Lark Plugin AI Builder CDN Build

This repository contains the static CDN build generated from `lark-plugin-ai-builder`.

## Contents

- `dist/`: production static assets for CDN deployment

## Build Source

- Source repository: `nest_back_all/lark-plugin-ai-builder`
- Source commit: `55c78a6`
- API base: `https://ai.cmarvel.cn`

## Rebuild

From the source repository:

```bash
pnpm --prefix lark-plugin-ai-builder run build:all
```

Then replace this repository's `dist/` directory with the generated `lark-plugin-ai-builder/dist/` directory.
