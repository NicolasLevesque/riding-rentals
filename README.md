# Riding Rentals 🏠📍

A rental search tool that filters apartment listings based on Canadian political ridings.

## Why

Most rental platforms let you search by neighborhood or city. But what if you're politically aware and want to live within a specific riding—like one represented by a Conservative or Liberal MP This project solves that.

## Features

- Input any federal riding (e.g. `Carleton`)
- Pulls rental listings from platforms using mapped postal prefixes
- Filters by price and parking
- Optional monetization logic for future upgrade tiers

## Tech Stack

- 🐍 Python (BeautifulSoup, Requests)
- 🌐 HTML React (frontend)
- 📫 API endpoint for riding-based rental lookups
- 💡 Potential StripePayPal monetization

## Demo

[Add link here if hosted]

## Run Locally

```bash
cd riding-rentals
python scraperrental_scraper.py --riding Carleton
```
