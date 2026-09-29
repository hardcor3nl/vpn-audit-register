# Changelog

## 2026-09-28
Initial compilation, 2026-09-28. 22 records.

## 2026-09-29 (corrections after independent audit)
- expressvpn incident: removed the DOJ deferred-prosecution and DarkMatter detail the cited page does not state.
- ipvanish incident: removed 'then owned by Highwinds' (source names StackPath as operator); parent Ziff Davis and 30-day yearly refund re-verified from ipvanish.com; HQ marked as inferred.
- purevpn incident reworded as 'reported by The Register'; 2023 audit no longer attributed to KPMG (not named on the assessment page).
- hide-me audit date confirmed from the PDF (document date 07.06.2024, fieldwork Mar-Jun 2024).
- plans: added billedMonths and replaced '1-year'/'2-year' labels with real term length (12, 13, 24, 26, 27, 28, 36 months); purevpn 1-year discrepancy documented.
- schema updated (term free string, billedMonths); METHOD.md updated (validated with jsonschema).

## 2026-09-29 (StrongVPN prices)
- strongvpn: https://strongvpn.com/pricing/ now returns 404; the current official page is https://strongvpn.com/plans/. Re-verified from it: monthly plan $11.99/mo; annual plan $3.97/mo billed $47.69 for the first year (renewal price not stated); 30-day money-back guarantee, annual plan only. Previous record had no verified prices (site had blocked earlier fetches).

## 2026-09-29 (wave 2 audit: currency reconciliation and corrections)
- surfshark, cyberghost: the 28 Sep register labelled USD, but the vendor pages read directly on 29 Sep showed euros (Surfshark: "may vary depending on the currency"; CyberGhost: "all amounts shown are in Euros"). Re-read a US-dollar copy of each page on 29 Sep: Surfshark $2.49/$67.23 (Starter, 27 months), CyberGhost $12.99 monthly, $6.99/$41.94 six-month and $2.19/$56.94 26-month. So both currencies exist. Long-plan numerals are identical in USD and EUR; CyberGhost's monthly price differs (USD 12.99, EUR 11.99). Both USD and EUR plan rows are now recorded, each with its currency and read date.
- ipvanish: privacy policy read 29 Sep: address in New York (HQ no longer "inferred"); the no-log policy also lists "connection time stamps" as not retained, alongside the session-data line; 24-month price $57.36 and renewal $99.99 confirmed on the vendor page (a cached copy read 29 Sep).
- pia: "general location for US sales tax" replaced with the page's wording (email, payment details and ZIP code); Kape RNS of 16 Dec 2019 added as the ownership source (replaces Wikipedia for the acquisition).
- public copy sites/vpninfobase/public/data/vpn-audit-register.json re-synced (it still carried the pre-29 Sep StrongVPN record).
