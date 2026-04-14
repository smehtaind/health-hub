# Health Hub

Personal health system — Indian vegetarian, ~1800 cal, 90g protein.

## Pages

| Page | What it covers |
|------|---------------|
| **/** | Hub — links to all three pages |
| **/plan** | Daily timeline — 5:55 AM to 10:30 PM, every eating block |
| **/kitchen** | Kitchen rules, portions, 60+ dish options with P/cal/insulin |
| **/blueprint** | The science — calories, BMR, macros, insulin, fat burning, diabetes |

## Deploy

### Option A — Vercel CLI
```bash
npx vercel
```

### Option B — GitHub → Vercel
1. Push this repo to GitHub
2. Go to [vercel.com/new](https://vercel.com/new)
3. Import the repo
4. Framework preset: **Other** (static)
5. Deploy

No build step needed. Pure static HTML.

## Local dev
```bash
npx serve .
```

## Stack
- Pure HTML + CSS + vanilla JS
- Plus Jakarta Sans (Google Fonts)
- Zero dependencies, zero build tools
- Vercel static hosting
