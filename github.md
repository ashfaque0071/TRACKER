repo: ashfaque0071/TRACKER
branch: main
path: index.html

## Last sync
date: 2026-08-15T21:40:00Z

### Updated in this project
- Dedicated phone layout at 820px and under: the whole app reflows to a single column with no horizontal scrolling anywhere.
- Transactions become stacked rows — description and amount on top, date · category · wallet beneath — and tap a row to expand a full-size editor.
- Every list (bills, subscriptions, wallets, lending, income, extras, held money, goals, debts, categories, statistics) has a phone layout with 40–46px controls.
- Phone header: month nav on its own row, a Sections sheet that jumps to any card, and a More sheet holding currency, rate, backup, restore, CSV and theme.
- Inputs render at 16px on phones so iOS Safari stops zooming on focus; safe-area insets respected in standalone mode.
- Service worker bumped to mt-v3 so installed copies pick the new shell up.

## Screen map
| Project file | Repo file |
| --- | --- |
| Money Tracker.dc.html (source of truth) | — |
| index.html (standalone export) | index.html |
| manifest.json | manifest.json |
| sw.js | sw.js |
| icon-192.png / icon-512.png / icon-180.png / favicon.png | same names |

## Sync history
- 2026-08-15T00:00:00Z · quick add multi-line + Again chips, keyboard shortcuts, linked refunds, wallet reconcile, backup-age stamp, PWA install.
- 2026-08-10T21:59:27Z · commit 8bbb947a6f88 · connected the repo; monthly periods, statistics, extra earnings, lending.
