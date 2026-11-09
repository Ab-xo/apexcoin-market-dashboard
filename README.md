# ApexCoin

A read-only cryptocurrency market dashboard for exploring digital assets, market activity, and historical price data. ApexCoin uses CoinGecko data and does not execute trades or provide financial advice.

## Features

- Global market capitalization, volume, and Bitcoin dominance overview
- Trending assets and categories
- Searchable, sortable, paginated coin screener
- Shareable coin detail pages
- Interactive OHLC candlestick charts with selectable ranges
- USD, EUR, GBP, and INR display options
- Responsive loading and error states

## Technology

| Area | Stack |
|---|---|
| Framework | Next.js App Router |
| UI | React, TypeScript, Tailwind CSS v4 |
| Components | Base UI, shadcn/ui configuration |
| Data | CoinGecko API |
| Tooling | npm, ESLint, TypeScript |

## Getting started

```bash
npm install
cp .env.example .env.local
npm run dev
```

Set `COINGECKO_API_KEY` and, if needed, `COINGECKO_BASE_URL` in `.env.local`. Keep the API key server-side.

## Commands

```bash
npm run dev
npm run lint
npx tsc --noEmit
npm run build
npm run start
```

## Routes

- `/` — product introduction
- `/market` — market overview
- `/coins` — asset screener
- `/coins/[id]` — asset details and price history

## Disclaimer

Market data may be delayed or incomplete. This project is for educational and portfolio purposes only and is not financial advice.
