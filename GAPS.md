# GAPS: fields not verified from a primary source

Compiled from the four research groups. Null in the JSON means unverified. vpnarea has no record (site returned HTTP 522 twice).


# Gaps, group 1 (checked 2026-09-28)
## nordvpn
- ultimateOwner: not stated on vendor pages
- audits: 2018 PwC report link; third review (Deloitte) date/link; 2023 and 2025 report links; exact dates for 2024/2025 not on page
- incidents: only the 2019 datacenter disclosure checked; no exhaustive news search
- transparency report: direct report URL not found (trust page only)
- open source: only Linux app confirmed
- plans: Basic tier only recorded (Complete/Prime in notes); 2-year per-month covers 27 months
## expressvpn
- ultimateOwner: only secondary source (Wikipedia); Kape stated as ultimate holding company in privacy policy
- plans: 1-month and 1-year prices not retrieved (JS tabs)
- audits: many report links not captured; list copied from vendor trust page
- incidents: no exhaustive search; only Gericke/DOJ (vendor blog)
- open source: partial (Lightway core) only
## surfshark
- ultimateOwner: null; only "merged under one holding company with Nord Security (2022)" per about page
- plans: 1-month and 1-year not retrieved; 2-year renewal price not stated
- openSourceClients: not verified
- audits: report-to-year mapping for Cure53/SecuRing PDFs inferred from page order; Deloitte reports need account login
- incidents: none found/checked exhaustively
## proton-vpn
- plans: all prices null (JS-rendered; Proton API refused); Free tier confirmed exists
- ramOnlyServers: not stated on pages reviewed
- audits: report URLs not captured; Securitum apps audit date unspecified
- incidents: none checked exhaustively
## pia
- parentCompany/ultimateOwner: Kape named only in privacy policy text; ultimate owner from Wikipedia only
- audits: 2022/2024 report links not captured; first-audit year from 2025 blog text
- plans: 2-year not offered (3-year exists); no separate renewal price stated
- incidents: none checked exhaustively
## cyberghost
- ultimateOwner: Wikipedia only; parent from privacy policy
- openSourceClients: not verified (no page found)
- audits: first audit date/link not read; 2024 date from URL/blog only
- plans: 1-year not offered on page; refund window read from money-back page (terms page did not state days)
- incidents: none checked exhaustively

# Gaps, group 2 (checked 2026-09-28)

## mullvad
- Transparency report: none found (published=null).
- openSourceClients: per-client claim not verified (about page says "majority" open source).
- Audits: reportUrl null for older audits (only the blog tag listing seen); auditor not named on listing for 2024-12, 2022-10, 2020-06, 2018-09; reportUrl for others is the announcement post, PDF not opened.
- 1-year/1-decade upfront totals not stated; 2-year not offered (decade term exists).

## ivpn
- Audits for 2022 (4th annual) and 2025 (7th annual, scheduled May 2025) and the July 2026 (8th) audit: results not found/verified.
- RAM-only: completion not verified (only "transition under way" May 2025).
- Open-source: not checked per repo.

## windscribe
- ultimateOwner: not verified (founders Sak, Paguis, Ulicki named on about page, share not stated).
- pricing page /features/pricing 404; used /upgrade (USD). Promo/renewal not confirmed; 2-year inferred not offered from absence on page.
- Packetlabs report URL not found (reportUrl null).
- Ukraine 2021 incident sourced only to Windscribe's own page (no external report fetched).

## tunnelbear
- ultimateOwner and current ownership (McAfee status after 2018, sale/rebrand) unverified; TunnelBear pages name only TunnelBear LLC.
- Plans: pricing page JS-rendered; only "from $3.33/mo" (term unstated) and Teams $5.75/user/mo seen; 1-month, 1-year, 2-year all null (plans empty).
- Transparency report, open-source clients, RAM-only: not verified.
- Incidents: none verified (no search of news done).
- Audit dates are blog publication dates; 2025 post covers audit done Oct-Nov 2024; no 8th report PDF link.

## ipvanish
- pricing/terms pages returned 403 to default fetch; used homepage pricing block (USD, promo vs renewal noted). Terms of Service page not retrieved (refund from money-back page).
- openSourceClients: not verified.
- Audit report PDFs are gated (account portal); reportUrl null. Earlier Leviathan audit (2018) not verified.
- ultimateOwner given as Ziff Davis, Inc. per privacy policy; no further owner tracing.
- HQ jurisdiction taken from vendor "US-based" statement; no state/registry checked.

## vyprvpn
- vyprvpn.com pricing, terms, privacy pages blocked by Cloudflare (403) after retries; certida.com terms/privacy are JS-rendered (Termly). Plans all null (plans empty).
- Ownership: vyprvpn.com/terms 301-redirects to certida.com/terms; Certida LLC (Austin TX) lists VyprVPN. Golden Frog GmbH (Switzerland) appears only in old (2021) pages. Sale date/ultimate owner unverified.
- Leviathan audit date null (report/blog show no date I could extract); later audits not found.
- Refund and logging text are from old Golden Frog pages, may be outdated.
- Transparency report, open source, RAM-only, incidents: not verified.

# Gaps, group 3 (checked 2026-09-28)

## hide-me
- ultimateOwner: not found (eVenture Limited is operator; no owner disclosed in pages read)
- Audit scope/details: Securitum PDF (2024-06-07 per filename) could not be read (WebFetch blocked for hide.me; no PDF text tool). Date inferred from filename. No 2015 audit report link found although about page says first audited 2015.
- ramOnlyServers, openSourceClients: not stated on pages read (no GitHub link found)
- incidents: none found; not exhaustively searched
- Refund conditions: terms text truncated; only 30-day window confirmed. Terms served at /en/legal.

## hotspot-shield
- hqJurisdiction: not verified from a primary page (policy names Intersections LLC / Pango GmbH; search snippets say US)
- ultimateOwner: not verified; Point Wild press release pages returned 403 (Aura split 2024-09 and Point Wild merger 2024-12 only from search snippets)
- Current privacy policy/ToS (legal.hotspotshield.com) returned 403; used 2022 policy and 2019 ToS versions, may be superseded
- plans: pricing pages 404/JS-rendered; all prices null (offered flags unverified)
- refundWindow: 45 days from homepage only; not confirmed in current terms
- transparencyReport: 2019 report reportedly published, later ones not found; URL not obtained. 2022 law-enforcement report mentioned by Aon.
- Audits: only Aon 2023 (summary). Earlier audits not searched. Aon report authorship read from PDF text.
- ramOnly, openSource: not stated in pages read
- incidents: only 2017 CDT complaint; 2017 vulnerability disclosure not sourced

## atlas-vpn
- status: service closed 2024-04-24 (Nord Security blog dated 2024-03-25; closure date is in snippet/headline). Atlas help page 403; atlasvpn.com 509.
- ultimateOwner, HQ, audits, logging claim, transparency, RAM, open source, refund: not sourced
- Incident date approximate (article 2023-09-05; original Reddit disclosure Aug 2023)

## privatevpn
- parentCompany: Miss Group Holdings acquisition from PitchBook search snippet only; not verified on a primary page
- ultimateOwner: unknown
- audits: none found (third-party reviews say none; not proof)
- 1-year price: promo 12+24 months at 2.00/mo for 36 months; renewal wording ambiguous; plain 12-month price not shown; 2-year plan not offered on page
- transparencyReport, RAM, openSource, incidents: not found/checked
- Prices are incl. VAT, USD default by geolocation

## strongvpn
- All vendor domains (strongvpn.com, support.strongvpn.com) returned 403 / blocked; web.archive.org unreachable
- Everything null except parentCompany (Wikipedia, secondary): ultimateOwner, HQ, audits, logging claim, incidents, transparency, RAM, open source, plans, refund

## trust-zone
- ultimateOwner: not disclosed; Internet Privacy Ltd only
- audits: none found on site (not searched externally)
- openSource, RAM: not stated on pages read
- Prices are promo (bonus-term) prices; renewal not stated; USD; 6-months-free coupon EXTRA shown
- incidents: none searched externally
- Refund conditions: 10 days for first purchase made directly

# Gaps, group 4 (checked 2026-09-28)

Note: airvpn.org serves only a JS/cookie gate page to non-browser clients (all pages return a stub); I did not work around the gate. vpnarea.com returned HTTP 522 on 2 tries (see vpnarea below). web.archive.org connections were reset.

## airvpn (record written, mostly null)
- parentCompany, ultimateOwner: not verified (secondary sources mention Air S.r.l., not confirmed at a primary source)
- hqJurisdiction: Italy from secondary source (ProPrivacy) only
- audits: none found (secondary sources say no independent audit); not confirmed at the vendor
- loggingPolicy: vendor's own text not read; claim taken from secondary source
- incidents, transparencyReport, ramOnlyServers: not verified
- openSourceClients: Eddie is GPLv3 (GitHub/GitLab), but completeness of all first-party clients not verified, so null
- plans (1-month, 1-year, 2-year, EUR): all prices null; 2-year offered per secondary source only
- refundWindow: null

## zenmate
- Status acquired-rebranded (service moved to CyberGhost apps 2023-03-16, ZenMate apps unsupported after 2023-05-01, new sign-ups stopped 2023-03-16) per zenmate.com/blog/zenmate-changes
- ultimateOwner: Kape takeover by Unikmind/Teddy Sagi verified only as agreed offer (Tech Monitor, Feb 2023); completion not verified
- audits: none found; loggingPolicy: homepage claim only, privacy policy not read
- incidents, transparencyReport, openSourceClients, ramOnlyServers: not verified
- plans: not offered; refundWindow: null (terms not read)

## vpnarea (NO RECORD WRITTEN)
- vpnarea.com returned 522 on 2 tries; nothing fetched. Not researched further within budget. All fields unverified.

## astrill
- ultimateOwner: not stated
- audits: none found; incidents: none verified; transparencyReport, openSourceClients, ramOnlyServers: not verified
- plans: pricing page shows a 'reseller coupon has been activated' banner, so displayed prices may be discounted; renewal prices not stated

## purevpn
- ultimateOwner: null (secondary sources point to Gaditek / Uzair Gadit, unverified)
- audits: KPMG 2021 date conflicts (vendor note Oct 2020 vs XDA Aug 2021); reports are behind an email gate, so reportUrl null; 2024 audit claimed by secondary sources, not verified; vendor pages anonymize the auditor name
- transparencyReport: purevpn.com/transparency-report returned 404; published=null
- openSourceClients, ramOnlyServers: not verified
- plans: upfront term lengths for promo prices not stated explicitly; renewal prices not stated
- incidents: 2017 FBI/Ryan Lin case verified via The Register; PureVPN's own response not read

## Added 2026-09-29 (post-audit)
- purevpn 1-year: cart plan is a 12-month interval, but $47.95/12 = 4.00/mo, not the displayed $2.55/mo; unresolved.
- trust-zone 1/2-year: billed period ambiguous ('X years + X years'); billedMonths null.
- airvpn 1-year/2-year: price and billing period not verified.
- ipvanish: HQ city not read; 'United States' is inferred from the parent Ziff Davis, Inc.'s US Data Privacy Framework certification. Refund (30 days on yearly or longer) and parent (Ziff Davis footer) verified on ipvanish.com home page.
- purevpn 2023 assessment: auditor not named on the assessment page; not attributed to KPMG here.
- expressvpn: the 29-entry audit list was copied from the vendor trust page and has not been independently second-checked; surfshark and nord audit dates unchecked.
- expressvpn incident: DOJ / DarkMatter legal detail removed (not in the cited vendor blog); would need a DOJ or news source.
