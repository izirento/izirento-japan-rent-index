# Japan: rent and landlord rules index 2026

Open, source-linked data on residential rent and landlord obligations in Japan: deposits, rent increases, termination notice, lease terms, registration and landlord duties, with a primary-source link for every value.

- Version: 1.0
- Facts checked: 2026-11-04
- Author: Leonid Gorok
- Project site: [izirento.com](https://izirento.com)
- Related: [UK Rent & Landlord Obligations Index 2026](https://izirento.com/en-gb/research/data/uk-rents-and-landlord-duties-index), [UK repository](https://github.com/izirento/izirento-uk-rent-index), [catalog of country repositories](https://github.com/izirento/izirento-rent-index-international)
- Licence: CC BY 4.0 (see [`LICENSE`](LICENSE) and [`LICENSE.md`](LICENSE.md)). Laws and official statistics are cited, not copied.

## Disclaimer

The data is provided as is, without any liability. We only collect and organise what the official sources publish. Laws change and local rules differ: always check each value against the primary source linked next to it before relying on it. This is information, not legal advice.

## Scope and limits

The text read comes from the e-Gov law database (Digital Agency) through its official data API: the Act on Land and Building Leases (Act No. 90 of 1991) and the Civil Code (Act No. 89 of 1896). Special rules for fixed-term leases entered before the 2000 amendment, for land leases, and for public or corporate housing were not covered. The rows are our English wording of the Japanese text; the Japanese text prevails.

## Key facts

| Topic | Field | Value | Source |
| --- | --- | --- | --- |
| tenancy_law | Main laws | Building leases are governed by the Act on Land and Building Leases (借地借家法, Act No. 90 of 1991) and by the lease provisions of the Civil Code (民法, Act No. 89 of 1896). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |
| deposit | Security deposit (shikikin): return | A landlord who has received a deposit (敷金, whatever it is called) must return the balance after deducting the tenant's unpaid money obligations when the lease has ended and the property is returned, or when the tenant lawfully assigns the lease; the landlord may apply it to unpaid debts, but the tenant may not demand that it be used for them (Civil Code Art. 622-2). The law sets no cap on the amount. | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/129AC0000000089) |
| rent_payment | Rent payment time | Unless agreed otherwise, rent for buildings is payable at the end of each month (Civil Code Art. 614). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/129AC0000000089) |
| rent_increase | Rent increase or decrease claim | Either party may claim an increase or decrease of building rent for the future if it has become unreasonable because of changes in taxes or other burdens, in land or building prices or economic conditions, or in comparison with similar buildings, regardless of the contract terms (Art. 32). A clause that rent will not be increased for a set period prevails. The Act sets no fixed percentage cap. | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |
| lease_term | Minimum fixed term | A building lease with a fixed term of less than one year is treated as a lease without a fixed term (Art. 29(1)). The 50-year maximum term of the Civil Code does not apply to building leases (Art. 29(2)). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |
| renewal | Renewal | If neither party gives notice of non-renewal (or notice of a change of terms) between one year and six months before the end of a fixed term, the lease is deemed renewed on the same terms, with no fixed term (Art. 26(1)); the same applies if the tenant stays on after expiry and the landlord does not object without delay (Art. 26(2)). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |
| termination | Landlord notice and just cause | When the landlord gives notice of termination, the lease ends six months after the notice (Art. 27(1)); a landlord's notice of non-renewal or termination is valid only if there is just cause, judged on the needs of both parties, the history of the lease, how the building is used, its condition and any payment offered for moving out (Art. 28). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |
| termination | Tenant notice (lease without fixed term) | For a lease with no fixed term, each party may give notice of termination at any time, and a building lease ends three months after the notice (Civil Code Art. 617(1)(ii)). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/129AC0000000089) |
| contract_form | Fixed-term lease without renewal | A fixed-term building lease that is not renewable can be made only in writing (for example a notarial deed, or an electronic record treated as writing), and the landlord must first give the tenant a separate written explanation that there is no renewal (Art. 38(1)-(3)). | [e-Gov Law Search (Digital Agency, Japan)](https://laws.e-gov.go.jp/law/403AC0000000090) |

## 日本語

**日本.** 賃貸と家主の義務に関するオープンデータ：敷金、賃料の増減、解約の通知期間、賃貸借契約。各値に公的な一次情報源へのリンクを付けています。

*データは現状のまま提供され、一切の責任を負いません。公的な情報源が公表している内容を整理しているだけです。法令は改正されますので、各値は記載の一次情報源で必ずご確認ください。*

Details: see the table above and `sources.md`.

## Files

| File | Content |
| --- | --- |
| `japan_rent_landlord_rules_2026.csv` | One row per fact, with source URL, optional cross-check URL and check date |
| `sources.md` | Every field with publisher and links, plus fields left empty and notes |
| `LICENSE`, `LICENSE.md` | CC BY 4.0 legal code; attribution and source statements |
| `CITATION.cff` | Citation metadata |

## Field dictionary

| Field | Meaning |
| --- | --- |
| `country_code, country` | Code and name |
| `topic` | Group: tenancy_law, deposit, rent_increase, rent_control, termination, contract_form, registration, rent_payment, landlord_duties, rent_level_change and similar |
| `field` | Specific item |
| `value` | The fact in our own words; empty where no verified figure was found |
| `source_publisher` | Body that publishes the source |
| `source_url` | Link to the primary source |
| `cross_check_url` | Second source actually read, if any |
| `checked_on` | Date the source was read |
| `note` | Scope, language of the source or caveat |

## Method

1. Each value comes from a primary source: the statute on the official legal portal, a government service page or a statistics office dataset. Where a second official or institutional page confirms it, that link is in `cross_check_url`.
2. Values are written in our own words. Nothing is estimated or calculated; where no verified value exists the cell is empty and the reason is given in `sources.md`.
3. Where a statute is translated or summarised from another language, the original-language text prevails.

## Citation

Gorok, L. (2026). *Japan: rent and landlord rules index 2026* (Version 1.0) [Data set]. IziRento. https://github.com/izirento/izirento-japan-rent-index

## Attribution

Sources are listed in `sources.md` and in `LICENSE.md`.
