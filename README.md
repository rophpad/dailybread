# Dailybread

Order breads and accompaniments online.

Live: [dailybread-store.vercel.app](https://dailybread-store.vercel.app)

## What it does

Dailybread is an online storefront for ordering bread and accompaniments. Browse the catalog, pick quantities, and review your order in a cart before checking out.

## Features

- **Product catalog** — browse bread items and accompaniments with images
- **Search** across products
- **Cart** with quantities and persisted state across reloads
- **Checkout** summary with payment box
- Responsive storefront layout

## Tech stack

- [Nuxt](https://nuxt.com) (App Router layout) + Vue 3
- [Pinia](https://pinia.vuejs.org) with persisted cart state
- [Nuxt UI](https://ui.nuxt.com) components
- Tailwind CSS

## Getting started

```bash
npm install
npm run dev
```

Open [http://localhost:3000](http://localhost:3000). Build for production with `npm run build`.

## Project structure

- `app/pages` — `index.vue` (catalog) and `cart.vue` (cart/checkout)
- `app/components` — BreadItem, BreadList, AccompanimentsList, SearchBar, PaymentBox, QuantitySelector
- `app/stores` — `cart`, `global`, `product` Pinia stores
- `app/data/datas.ts` — product seed data
- `public/breads` — product images

## Status

Active project. Default Nuxt template README replaced on 2026-09; feature set reflects the current codebase.