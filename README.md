# SMM Panel Guide — Beginner's Handbook (Hindi + English)

![Guide](https://img.shields.io/badge/Guide-Beginner-FF6B35?style=flat-square) ![Language](https://img.shields.io/badge/Language-Hindi%20%2B%20English-0A66C2?style=flat-square) ![Updated](https://img.shields.io/badge/Updated-2026-00B67A?style=flat-square)

A plain-language guide to SMM panels for creators, small businesses and first-time resellers in India. Maintained by the team behind https://topsmm.in

## Contents

| Section | What it covers |
| --- | --- |
| SMM panel kya hota hai | The basics in Hindi and English |
| How a panel actually works | Provider chain, auto start, delivery |
| Choosing a panel | What separates a good panel from a bad one |
| Glossary | Drip feed, refill, mass order, API and more |
| Pricing | How per-1000 rates work and where margin comes from |
| Reseller FAQ | Starting your own panel on an API |
| Safety | What to avoid so accounts stay healthy |

## SMM panel kya hota hai?

SMM panel ek online dashboard hota hai jahan se aap social media marketing services order karte hain — Instagram followers aur likes, YouTube views aur subscribers, Facebook page likes, Telegram members aur bahut kuch. Aap service choose karte hain, apna link daalte hain, quantity select karte hain, aur order place ho jata hai. Delivery automatically shuru hoti hai aur aap dashboard me live progress dekh sakte hain.

In English: an SMM panel is a self-serve marketplace for social media marketing services. Instead of negotiating with suppliers one by one, you buy from a catalogue at a fixed rate per 1000 units and track everything from one dashboard.

## How a panel actually works

Most panels do not produce the delivery themselves. They sit on top of a chain of providers and resell capacity.

| Step | What happens |
| --- | --- |
| 1 | You place an order and the panel charges your balance |
| 2 | The panel forwards the order to the provider behind that service |
| 3 | The provider starts delivery, usually within seconds on auto start services |
| 4 | The panel polls the provider and updates status, start count and remaining |
| 5 | On completion the order is closed; partial orders are refunded automatically |

This is why two panels can sell the same service at different prices and different quality — they are buying from different points in that chain.

## Choosing a panel

| Check | Why it matters |
| --- | --- |
| Auto start | Without it your order waits in a manual queue, sometimes for hours |
| Refill guarantee | Followers drop. A refill window decides who pays for that drop |
| Live order tracking | Start count and remaining tell you whether delivery is real |
| Partial refunds | A fair panel refunds the undelivered part automatically |
| Payment options | UPI and local methods matter for Indian buyers |
| Real support | Test the support channel before you deposit a large amount |
| Public reviews | Independent reviews, not screenshots on the panel's own site |

Start with a small deposit and one small order on any new panel. Judge start time, drop rate after 72 hours and how support replies when something fails.

## Glossary

| Term | Meaning |
| --- | --- |
| Auto start | Order begins processing immediately, no manual approval |
| Drip feed | Delivery split into runs over time so growth looks natural |
| Mass order | Many orders submitted in one paste, one per line |
| Refill | Free top-up when counts drop inside the guarantee window |
| Start count | The follower or view count recorded when the order began |
| Partial | Order delivered partly; the rest is refunded |
| Per 1000 rate | Catalogue price for 1000 units of a service |
| API key | Secret token that lets your software place orders programmatically |
| Provider | The upstream supplier a panel buys delivery from |

## Pricing

Rates are quoted per 1000 units. If a service costs 10 rupees per 1000 and you order 500, the charge is 5 rupees. Reseller margin is the gap between your buying rate on a wholesale panel and the retail price you charge your own customers — most small panels run on a 30 to 100 percent markup depending on support load.

Cheaper is not always better. A very low rate usually means a weaker provider further down the chain, which shows up as slow starts and high drop rates.

## Reseller FAQ

**Do I need my own website to resell?**
No. Many resellers start by taking orders on WhatsApp or Instagram and placing them manually on a wholesale panel. A website or your own panel becomes worth it once order volume makes manual work painful.

**How do I automate it?**
Use the panel's API. You pull the service list, place orders and poll status from your own script or panel software. See https://github.com/topsmm-in/smm-panel-api-docs for a full API reference.

**How much money do I need to start?**
Enough for a few test orders plus your first customer orders. Most Indian resellers start under 1000 rupees and reinvest.

**What causes orders to fail most often?**
A wrong link format, a private account, or a quantity outside the service min and max. Validate the link before submitting.

**Why did my followers drop?**
Platforms periodically remove inactive or flagged accounts. This is normal; it is why refill guarantees exist. Pick services with a refill window for anything you resell.

## Safety

Never share your account password with a panel or a seller — legitimate services only need your public profile or post link. Keep the account public while an order is running. Avoid ordering huge quantities on a brand new account; grow in steps. Treat your API key like a password and rotate it if it leaks.

## About the maintainers

This guide is maintained by the team at TopSMM, an Indian SMM panel and reseller API provider based in Hinjewadi, Pune.

| | |
| --- | --- |
| Panel | https://topsmm.in |
| API docs | https://github.com/topsmm-in/smm-panel-api-docs |
| Hindi video tutorials | https://www.youtube.com/@topsmm_in |
| Telegram | https://t.me/topsmm_in |
| Reviews | https://www.trustpilot.com/review/topsmm.in |

Corrections and additions are welcome — open an issue or a pull request.
