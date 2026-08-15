repo: ashfaque0071/TRACKER
branch: main
path: index.html

## Last sync
date: 2026-08-16T00:00:00Z

### Updated in this project
- Spending captured from SMS: bKash and bank messages forwarded from an Android phone arrive as transactions within 15 seconds, then are deleted from the inbox table.
- Parser reads BRAC card purchases, bKash merchant payments, send money and bill payments; incoming money, OTPs and promos are ignored, fees fold into the amount.
- bKash bill payments tick the matching bill instead of adding a duplicate row; matched by bill name in the message, else by amount.
- Categories are guessed from the merchant and learned when corrected — the merchant map syncs across devices.
- Imported rows are flagged unreviewed with an amber dot and a banner; "Looks right" or changing the category clears the flag.
- Setup panel carries the inbox SQL, webhook URL, headers and body, and lists any message the parser could not read.
- Service worker bumped to mt-v5.

## Screen map
| Project file | Repo file |
| --- | --- |
| Money Tracker.dc.html (source of truth) | — |
| index.html (standalone export) | index.html |
| manifest.json | manifest.json |
| sw.js | sw.js |
| icon-192.png / icon-512.png / icon-180.png / favicon.png | same names |

## Sync history
- 2026-08-15T21:40:00Z · phone layout at 820px and under; stacked rows everywhere, Sections and More sheets, 16px inputs; mt-v4.
- 2026-08-15T00:00:00Z · quick add multi-line + Again chips, keyboard shortcuts, linked refunds, wallet reconcile, backup-age stamp, PWA install.
- 2026-08-10T21:59:27Z · commit 8bbb947a6f88 · connected the repo; monthly periods, statistics, extra earnings, lending.
