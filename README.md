# US import duty on apparel by country of origin (October 2026)

**What this is.** A one-table summary of the duty a US importer pays on a typical apparel garment, by country of origin, as of October 26, 2026. It covers the Section 301 forced-labor action that took effect on July 24, 2026, the normal most-favored-nation (MFN) rate, and the legacy Section 301 duty on China. Each row cites its source.

**File:** `us-apparel-import-duty-by-origin-2026-10.csv` (7 rows, 8 columns)

| Column | Meaning |
|---|---|
| `origin` | Country or trade-agreement group |
| `typical_us_duty` | Typical total US duty on a cotton knit garment with a 16.5% MFN reference rate, as published. Text values and ranges are used where one number would mislead, for example China at 36 to 52% across HTS codes |
| `section_301_forced_labor_duty` | The additional Section 301 forced-labor duty set for that origin |
| `exempt_from_section_301` | Yes for goods that qualify under USMCA or CAFTA-DR; No otherwise |
| `eu_uk_duty` | Duty into the EU and UK where confirmed. Blank means not covered in this file |
| `watch_for_2027` | What could change the figure |
| `source` | Where the figure was read |
| `as_of` | The date the figures are valid for (YYYY-MM-DD) |

**What it covers.** Colombia, Mexico and Canada (USMCA), Central America (CAFTA-DR), Vietnam, India, Bangladesh and China. Primary sources: the USTR Federal Register notice of July 23, 2026, CBP guidance CSMS #69326983, and the European Commission TARIC database for EU duty. Federal Register notices of October 7 and October 26, 2026 were reviewed; neither changes apparel rates.

**What it does not cover.**
- 2027 rates. None have been published; any figure quoted for 2027 is an estimate.
- The exact rate for a given product. MFN varies by HTS code, so confirm classification and duty per shipment with a licensed customs broker.
- Merchandise processing fee, harbor maintenance fee, freight, insurance, quotas or anti-dumping measures.
- Origins not listed, such as Portugal, Turkey or Indonesia.
- Legal or customs advice.

**Two results to read from it.**
- Colombia pays 12.5% typical with a certificate of origin, and about 29% without it. The certificate removes the MFN base, not the 12.5% Section 301 duty. Colombia is not exempt from it.
- Qualifying USMCA and CAFTA-DR goods pay 0%, so Colombia is 12.5 points behind them when the garment qualifies.

**Who compiled it.** José Olarte, CEO of Tulum Fashions S.A.S., a Colombian apparel manufacturer in Medellín with a showroom in Los Angeles. The author's company manufactures in Colombia, so weigh this accordingly; the figures come from government sources and the file shows the origins where Colombia loses as plainly as the others.

**Full write-up with method and references:** https://doi.org/10.5281/zenodo.23682720
**Planning guide with a table by origin and a production calendar:** https://tulumfashions.net/guides/swimwear-apparel-sourcing-2027/

**Cite as:** Olarte, J. (2026). US import duty on apparel by country of origin, October 2026 (Version 1.0). Tulum Fashions S.A.S. https://doi.org/10.5281/zenodo.23682720

**License:** CC BY 4.0. Educational only; not legal or customs advice.
