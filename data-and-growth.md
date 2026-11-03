# Data and growth: what the numbers said

A write-up of how I used data on the digital side of Velux Detailing, my brother's mobile car detailing business in the West Midlands. Sources: Google Analytics 4 (60 days), Google Search Console (90 days), Lighthouse, and live Google results via DataForSEO, all pulled through a custom tool (an MCP server I wrote) so I could query them in plain English. Period: August–November 2026.

## 1. Where visitors came from (GA4, 60 days, ~670 sessions)

| Channel | Sessions | Lead actions* |
|---|---|---|
| Paid search (Google Ads) | 366 (55%) | 115 |
| Direct | 144 | 45 |
| Organic search | 108 (16%) | 76 |
| Organic social | 34 | 6 |
| AI assistants | 4 | 5 |

\*Quote form submissions, call clicks and WhatsApp clicks.

**Finding:** paid search drove over half of all visits, landing mostly on the Full Valet page (339 sessions, 106 lead actions). When ads were paused during a break in bookings, traffic fell to a few visits a day. Organic visitors were the highest quality, at 76 actions from 108 sessions.

**Caveat I had to account for:** after adding a cookie banner (consent mode), GA4 only records visitors who accept, so later form counts in GA4 were far below the real enquiries in the database. I treated the database as the source of truth for leads and GA4 for traffic patterns.

## 2. Devices

71% of sessions were on mobile. A walkthrough on a real phone size showed the homepage's first screen was only a photo: the headline, prices and the Book button were below the fold and behind the cookie banner. I rebuilt the mobile hero so they're visible immediately and made the cookie bar a single line.

## 3. Search visibility (Search Console, 90 days)

- ~80 clicks in total, about a third from people searching the brand name.
- Main local searches ranked on pages 4–6 (for example "car detailing birmingham" at position 55).
- **Closest opportunities:** "ceramic coating west midlands" (position 10–11) and "mobile rolls royce detailing" (position 9). I wrote case-study pages to support the second.
- The booking page appeared thousands of times for product searches like "car wax", which have no buying intent for a service. I treated those impressions as noise rather than a win.

## 4. Why it ranked badly: diagnosis

| Possible cause | Checked | Result |
|---|---|---|
| Slow site | Lighthouse, mobile and desktop | 98–100 performance, not the problem |
| Technical SEO | Lighthouse SEO, sitemap, canonical tags, redirects | 100, not the problem |
| Authority | Backlink profile | 31 linking domains, mostly low-quality: **the main problem** |
| Local pack (Google Maps) | Live results for key searches | Top 3 in Wolverhampton had only 14–23 reviews, so it's achievable with reviews and profile activity |

**Conclusion:** more website work wouldn't move rankings. The levers were the Google Business Profile (reviews, weekly posts, accurate services and prices), consistent local directory listings, and genuine local links, plus restarting paid search when the business could take bookings again.

## 5. What I changed because of the data

- Built **prepaid packs, gift vouchers, a subscription and a referral scheme** to earn from existing customers while paid traffic was paused.
- Added **case studies** for the searches that were closest to page one.
- Fixed the **mobile first screen** and **accessibility** (contrast, labels, tap targets).
- Wrote a **Google Business Profile plan**: services and prices synced with the site, a review target, weekly posts and a directory list.
- Kept a **decision log** (through the same tool) so each change has a date and a check-back date.

## Skills shown

Defining the right question, combining several data sources, spotting measurement problems (consent mode), separating signal from noise (irrelevant search impressions), root-cause diagnosis, and turning findings into specific product and marketing actions.
