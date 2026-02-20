# Edelmon

A minimal, mobile-friendly Gold & Silver price tracker. Live prices update every 60 seconds with EUR conversions and the Gold/Silver ratio.

**[Live Demo](https://jensblond.github.io/edelmon/)**

## Features

- Real-time Gold (XAU) and Silver (XAG) prices in USD
- EUR per ounce and per gram conversions
- Gold/Silver ratio
- Percentage change between refreshes
- Auto-refresh every 60s, plus manual refresh
- Light and dark mode (follows system preference)
- Mobile-first, single-file, zero dependencies

## Data Sources

Prices are fetched with automatic fallback:

1. [gold-api.com](https://gold-api.com)
2. [goldprice.org](https://goldprice.org)
3. [metals.dev](https://metals.dev) (requires API key via `?metals_key=` URL param)

EUR exchange rate via [Frankfurter API](https://frankfurter.dev).

## Usage

Open `index.html` in a browser — that's it. No build step, no server required.
