# Method: VPN Ownership & Audit Register

Checked 2026-09-28. 22 records from the 25-entry list in the old site's `src/lib/vpnDatabase.ts` (used as a list of names only; its data was not used).

## Included / excluded
- vpnarea: no record; vpnarea.com returned HTTP 522 on two tries (see GAPS.md).
- Tor Browser: not a VPN; Proton VPN Free: a tier of Proton VPN, noted in that record. See `parts/excluded.md`.
- Discontinued or rebranded services (Atlas VPN, ZenMate) are kept with `status` set and sourced, because the old site listed them.

## Sources
Vendor pricing, terms, privacy and audit pages first; the auditors' own pages; GitHub for client source; named news outlets for incidents. Where only a secondary source (Wikipedia, PitchBook, The Register) was available it is named in the field's Source or in the field text. Every factual field has a `<field>Source` or a `sources` entry.

## Fields
- Prices are the monthly-equivalent shown by the vendor in the source currency; promo versus renewal is in `note`. `offered=false` means the term was not found on the vendor page (for Hotspot Shield and StrongVPN it means unverified). No conversions are made.
- Claims (logging, RAM-only) are the vendor's, paraphrased, not verified findings.
- `openSourceClients` is true only if every first-party client is open source.

## Known weaknesses
Many pricing pages are JS-rendered or blocked (Cloudflare 403) for non-browser clients; incident lists are limited to what was sourced and are not exhaustive; ultimate-owner fields are often null. All 22 records validate against schema.json (jsonschema, Draft 2020-12, checked 2026-09-29); this is a first pass and still needs periodic re-verification.

## Re-check cadence
Prices and refund terms every 90 days; ownership, audits and incidents every 90 days or on news.


## Plan terms
`term` is the real billed period in months (e.g. `13-month`, `26-month`, `36-month`), not a marketing label; `billedMonths` holds the number. `pricePerMonth` is the vendor's displayed monthly-equivalent for that whole period (bonus months included), so rows with different billedMonths are not like-for-like. Where the billed period could not be verified, billedMonths is null and the term carries a '(billing period not verified)' suffix.
