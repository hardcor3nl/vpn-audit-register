# VPN Ownership and Audit Register

Owner, headquarters jurisdiction, independent audits, incidents, logging-policy claims, RAM-only and open-source statements, transparency reports and price per month by billed term for 22 VPN providers. Every field links to the page it came from and carries the date it was checked. Logging and RAM-only entries are vendor claims; an audit is what tests a claim. Empty means not found in the sources read, never a guess.

- Canonical page: https://vpninfobase.com/vpn-audit-register/
- Statistics computed from this dataset: https://vpninfobase.com/vpn-audit-register/statistics/
- Version: 2026-09-29 (the date the data was last checked)
- Publisher: VPNInfobase editorial, an independent research publication at https://vpninfobase.com
- Size: 22 providers

## Files

| File | Contents |
|---|---|
| `vpn-audit-register.csv` | CSV, UTF-8. One row per provider. 22 rows. |
| `vpn-audit-register-audits.csv` | CSV, UTF-8. One row per recorded audit. 95 rows. |
| `vpn-audit-register-incidents.csv` | CSV, UTF-8. One row per recorded incident. 11 rows. |
| `vpn-audit-register-plans.csv` | CSV, UTF-8. One row per plan term, price in the vendor's own currency. 64 rows. |
| `vpn-audit-register.json` | The full dataset as JSON, including nested fields. |
| `schema.json` | JSON Schema for the main file. |
| `METHOD.md` | How the data was compiled and derived. |
| `GAPS.md` | What is missing or unverified. |
| `CHANGELOG.md` | Dated change log. |
| `CITATION.cff` | Citation metadata (Citation File Format 1.2.0). |

## Source method

Every fact traces to a primary source (vendor, government, or a named independent reviewer) linked in the row it belongs to, with the date it was checked. Values are stored as the source states them; nothing is converted between currencies. Empty or null means the source did not state it or could not be read, never a guess. Read METHOD.md for the full rules and GAPS.md for what is missing. We compile from public pages and do not run our own tests.

## Licence

Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/. You may copy, redistribute and adapt the data, including commercially, if you give credit and **link to the canonical page**: https://vpninfobase.com/vpn-audit-register/. Suggested credit: "Data: VPN Ownership and Audit Register by VPNInfobase, https://vpninfobase.com/vpn-audit-register/".

## Cite

VPNInfobase editorial. (2026). *VPN Ownership and Audit Register* (Version 2026-09-29) [Data set]. VPNInfobase. https://vpninfobase.com/vpn-audit-register/

Machine-readable citation: see `CITATION.cff`.

## Corrections

If you find an error, tell us through the contact page on https://vpninfobase.com. Corrections are logged in CHANGELOG.md.
