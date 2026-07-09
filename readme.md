# Lark Plugin AI Builder CDN Build

This repository contains the static CDN build generated from `lark-plugin-ai-builder`.

## Contents

- `dist/`: production static assets for CDN deployment

## Build Source

- Source repository: `nest_back_all/lark-plugin-ai-builder`
- Source commit: `33fab4d`
- API base: `https://ai.cmarvel.cn`

## Rebuild

From the source repository:

```bash
pnpm --prefix lark-plugin-ai-builder run build:all
```

Then copy the generated files into this repository's `dist/` directory. Keep older hashed files in
`dist/assets/` so cached plugin entry files can still load their matching chunks.
