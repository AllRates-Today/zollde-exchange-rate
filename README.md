# German Customs (Zoll) Exchange Rates API — zollde-exchange-rate

[![npm version](https://img.shields.io/npm/v/zollde-exchange-rate.svg)](https://www.npmjs.com/package/zollde-exchange-rate)
[![license](https://img.shields.io/npm/l/zollde-exchange-rate.svg)](https://github.com/AllRates-Today/zollde-exchange-rate/blob/main/LICENSE)
[![zero dependencies](https://img.shields.io/badge/dependencies-0-brightgreen.svg)](https://www.npmjs.com/package/zollde-exchange-rate)
[![TypeScript](https://img.shields.io/badge/TypeScript-types%20included-3178C6.svg)](https://www.typescriptlang.org/)
[![EUR/USD today](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fzollde%3Fsource%3DEUR%26target%3DUSD&query=%24.rate&label=EUR%2FUSD%20official%2C%20German%20Customs%20(Zoll)&color=0A7E8C&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/zollde/)
[![rate date](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fallratestoday.com%2Fapi%2Fopen%2Fcentral-bank%2Fzollde%3Fsource%3DEUR%26target%3DUSD&query=%24.rate_date&label=rate%20date&color=555&cacheSeconds=3600)](https://allratestoday.com/tax-authority-rates-api/zollde/)

**Official German Customs (Zoll) (Germany) monthly exchange rates for Node.js and TypeScript. The published tax authority rates behind tax filings, customs valuations, audits, and compliant invoicing — not market estimates, but the numbers German Customs (Zoll) itself prints, every month.**

## 🚀 Why this client?

- 🏛️ **Official rates** — German Customs (Zoll)'s own table, with the publisher's own `rate_date` on every response
- 📅 **History back to 2004** — point-in-time tables and daily series for any past date
- 🔀 **Official vs derived, always flagged** — computed inverse/cross pairs carry `derived: true`, never mixed with official prints
- ⚡ **Zero dependencies** — pure ESM + CJS over global `fetch`; Node 18+, Bun, Deno, and edge runtimes
- 🔷 **Type-safe** — full TypeScript definitions shipped with the package
- 🧾 **Compliance-grade metadata** — `rate_type`, publication date, and source disclaimer on every response

> **Official rate, not mid-market:** every value here is a number German Customs (Zoll) itself published, fixed once printed and carrying the tax authority's own `rate_date` — what filings and audits require. Need the live mid-market rate for pricing or display instead? Use the [mid-market API](https://allratestoday.com/docs/) or [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk). The two can diverge by several percent.

## 🔑 Get your API key

Get a free API key at [allratestoday.com/register](https://allratestoday.com/register) — no credit card required. Latest rates are on every plan, including free.

## 📈 Latest official table

[![Latest German Customs (Zoll) table](https://allratestoday.com/api/open/central-bank/zollde/table.svg)](https://allratestoday.com/tax-authority-rates-api/zollde/)

The image is rendered live from the keyless endpoint, so it follows the tax authority's publications on npm and on GitHub alike without a new release. The same table as text is folded below for search and copy-paste: on GitHub [a daily Action](.github/workflows/daily-table.yml) refreshes it whenever the tax authority publishes a new table; on npm it is as of the package's publish date.

<!-- daily-table:start -->
<details>
<summary>Table as text: published 2026-11-01 by German Customs (Zoll) — 118 rates, first 60 shown. Updated 2026-11-25.</summary>

| Base | Quote | Type | Rate |
| --- | --- | --- | ---: |
| EUR | AED | monthly | 4.17012 |
| EUR | AFN | monthly | 73.7635 |
| EUR | ALL | monthly | 92.05 |
| EUR | AMD | monthly | 412.14 |
| EUR | AOA | monthly | 1036.803 |
| EUR | ARS | monthly | 1714.8025 |
| EUR | AUD | monthly | 1.5971 |
| EUR | AWG | monthly | 2.03295 |
| EUR | AZN | monthly | 1.9264 |
| EUR | BAM | monthly | 1.95583 |
| EUR | BBD | monthly | 2.27973 |
| EUR | BDT | monthly | 139.2916 |
| EUR | BHD | monthly | 0.42648 |
| EUR | BIF | monthly | 3414.27945 |
| EUR | BMD | monthly | 1.1357 |
| EUR | BOB | monthly | 13.7055 |
| EUR | BRL | monthly | 5.6432 |
| EUR | BYN | monthly | 3.4323 |
| EUR | BZD | monthly | 2.2726 |
| EUR | CAD | monthly | 1.5779 |
| EUR | CDF | monthly | 2578.91 |
| EUR | CHF | monthly | 0.9256 |
| EUR | CLP | monthly | 1098.3 |
| EUR | CNY | monthly | 7.4999 |
| EUR | COP | monthly | 3793.967 |
| EUR | CRC | monthly | 518.17975 |
| EUR | CVE | monthly | 110.265 |
| EUR | CZK | monthly | 24.262 |
| EUR | DJF | monthly | 201.802 |
| EUR | DKK | monthly | 7.4746 |
| EUR | DOP | monthly | 68.4304 |
| EUR | DZD | monthly | 151.8231 |
| EUR | EGP | monthly | 59.03475 |
| EUR | ETB | monthly | 183.3751 |
| EUR | FJD | monthly | 2.56344 |
| EUR | GBP | monthly | 0.83825 |
| EUR | GEL | monthly | 2.9552 |
| EUR | GHS | monthly | 13.27845 |
| EUR | GIP | monthly | 0.85463 |
| EUR | GMD | monthly | 85.81 |
| EUR | GNF | monthly | 9987.1359 |
| EUR | GTQ | monthly | 8.67358 |
| EUR | GYD | monthly | 237.61 |
| EUR | HKD | monthly | 8.8155 |
| EUR | HNL | monthly | 30.61415 |
| EUR | HUF | monthly | 365 |
| EUR | IDR | monthly | 20269.17 |
| EUR | ILS | monthly | 3.4726 |
| EUR | INR | monthly | 106.1265 |
| EUR | IQD | monthly | 1481.8275 |
| EUR | IRR | monthly | 1974353 |
| EUR | ISK | monthly | 136.2 |
| EUR | JMD | monthly | 179.82375 |
| EUR | JOD | monthly | 0.80436 |
| EUR | JPY | monthly | 177.36 |
| EUR | KES | monthly | 147.22 |
| EUR | KGS | monthly | 99.2363 |
| EUR | KHR | monthly | 4624 |
| EUR | KRW | monthly | 1489.15 |
| EUR | KWD | monthly | 0.35032 |

</details>

[Full table on the German Customs (Zoll) rates page](https://allratestoday.com/tax-authority-rates-api/zollde/) · Source: [Official rates published by ZOLLDE, served by AllRatesToday](https://allratestoday.com/tax-authority-rates-api/zollde/). Rates are as printed by the tax authority; AllRatesToday is not affiliated with it.
<!-- daily-table:end -->

## 📦 Installation

```bash
npm install zollde-exchange-rate
```

```bash
yarn add zollde-exchange-rate
```

```bash
pnpm add zollde-exchange-rate
```

Requires Node 18+ (global `fetch`); also runs on Bun, Deno and edge runtimes. Also published under the org scope as [`@allratestoday/zollde-exchange-rate`](https://www.npmjs.com/package/@allratestoday/zollde-exchange-rate) — same code, same versions.

## 🏁 Quick start

```js
import { getRate } from 'zollde-exchange-rate';

const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
console.log(pair.rate, pair.rate_date); // the official German Customs (Zoll) rate, on the tax authority's own date
```

## 📚 API reference

- [Latest pair rate](#latest-pair-rate) — one pair from the latest official table
- [Full official table](#full-official-table) — everything the tax authority printed, in one call
- [Table for a date](#table-for-a-date) — the official table for an invoice or filing date
- [Daily time series](#daily-time-series) — one pair across a date range

---

### Latest pair rate

Free plan and up. Pairs the tax authority does not print directly are resolved from its table and flagged (see *Official vs derived rates* below).

```js
const pair = await getRate('USD', 'EUR', { apiKey: 'art_live_...' });
```

**Response:**

```javascript
{
  bank: 'zollde',
  name: 'German Customs (Zoll)',
  rate_date: '2026-11-01',   // German Customs (Zoll)'s own publication date
  source: 'USD',
  target: 'EUR',
  rate: 0.890155,
  rate_type: 'monthly',
  derived: true,
  method: 'inverse',  // computed from the published EUR/USD print
  disclaimer: 'Official rates as published by the named central bank. On weekends/holidays the most recent published rate_date is returned.'
}
```

### Full official table

Free plan and up. The complete table for the latest publication date.

```js
import { getLatestRates } from 'zollde-exchange-rate';

const table = await getLatestRates({ apiKey: 'art_live_...' });
console.log(table.rate_date, table.rates.length);
```

**Response:**

```javascript
{
  bank: 'zollde',
  name: 'German Customs (Zoll)',
  rate_date: '2026-11-01',
  rates: [
    { "base": "EUR", "quote": "USD", "type": "monthly", "value": 1.1234 },
    // … the rest of the official table (119 currencies vs EUR)
  ],
  disclaimer: '…'
}
```

### Table for a date

Paid plans. The official table for any date since 2004 — weekends and holidays return the most recent published date, flagged via `published_on_requested_date`, which is exactly the in-force rate a filing needs.

```js
import { getRatesForDate } from 'zollde-exchange-rate';

const day = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...' });
// Optionally narrow to one pair:
const one = await getRatesForDate('2026-06-30', { apiKey: 'art_live_...', source: 'USD', target: 'EUR' });
```

**Response:**

```javascript
{
  bank: 'zollde',
  requested_date: '2026-06-30',
  rate_date: '2026-06-30',                // the date actually published
  published_on_requested_date: true,      // false when a weekend/holiday fell back
  rates: [ /* the full table for that date */ ],
  disclaimer: '…'
}
```

### Daily time series

Paid plans. One resolved rate per publication date — ready for charting, revaluation runs, or audit workpapers.

```js
import { getHistory } from 'zollde-exchange-rate';

const series = await getHistory(
  { source: 'USD', target: 'EUR', from: '2026-01-01', to: '2026-11-01' },
  { apiKey: 'art_live_...' }
);
```

**Response:**

```javascript
{
  bank: 'zollde',
  source: 'USD',
  target: 'EUR',
  from: '2026-01-01',
  to: '2026-11-01',
  count: 152,
  rates: [
    // one entry per publication date
    { date: '2026-11-01', rate: 0.890155, rate_type: 'monthly', derived: true, method: 'inverse' },
    // …
  ],
  disclaimer: '…'
}
```

Pass `{ symbol: 'USD' }` instead of `source`/`target` to get the raw published rows for one currency (all rate types, no pair resolution).

---

## 🗺️ Currencies covered

German Customs (Zoll) currently publishes rates covering **119 currencies** against the EUR (as of the latest table):

🇦🇪 `AED` · 🇦🇫 `AFN` · 🇦🇱 `ALL` · 🇦🇲 `AMD` · 🇦🇴 `AOA` · 🇦🇷 `ARS` · 🇦🇺 `AUD` · 🇦🇼 `AWG` · 🇦🇿 `AZN` · 🇧🇦 `BAM` · 🇧🇧 `BBD` · 🇧🇩 `BDT` · 🇧🇬 `BGN` · 🇧🇭 `BHD` · 🇧🇮 `BIF` · 🇧🇲 `BMD` · 🇧🇴 `BOB` · 🇧🇷 `BRL` · 🇧🇾 `BYN` · 🇧🇿 `BZD` · 🇨🇦 `CAD` · 🇨🇩 `CDF` · 🇨🇭 `CHF` · 🇨🇱 `CLP` · 🇨🇳 `CNY` · 🇨🇴 `COP` · 🇨🇷 `CRC` · 🇨🇻 `CVE` · 🇨🇿 `CZK` · 🇩🇯 `DJF` · 🇩🇰 `DKK` · 🇩🇴 `DOP` · 🇩🇿 `DZD` · 🇪🇬 `EGP` · 🇪🇹 `ETB` · 🇫🇯 `FJD` · 🇬🇧 `GBP` · 🇬🇪 `GEL` · 🇬🇭 `GHS` · 🇬🇮 `GIP` · 🇬🇲 `GMD` · 🇬🇳 `GNF` · 🇬🇹 `GTQ` · 🇬🇾 `GYD` · 🇭🇰 `HKD` · 🇭🇳 `HNL` · 🇭🇺 `HUF` · 🇮🇩 `IDR` · 🇮🇱 `ILS` · 🇮🇳 `INR` · 🇮🇶 `IQD` · 🇮🇷 `IRR` · 🇮🇸 `ISK` · 🇯🇲 `JMD` · 🇯🇴 `JOD` · 🇯🇵 `JPY` · 🇰🇪 `KES` · 🇰🇬 `KGS` · 🇰🇭 `KHR` · 🇰🇷 `KRW` · 🇰🇼 `KWD` · 🇰🇿 `KZT` · 🇱🇦 `LAK` · 🇱🇧 `LBP` · 🇱🇰 `LKR` · 🇱🇾 `LYD` · 🇲🇦 `MAD` · 🇲🇩 `MDL` · 🇲🇬 `MGA` · 🇲🇰 `MKD` · 🇲🇳 `MNT` · 🇲🇴 `MOP` · 🇲🇺 `MUR` · 🇲🇻 `MVR` · 🇲🇼 `MWK` · 🇲🇽 `MXN` · 🇲🇾 `MYR` · 🇲🇿 `MZN` · 🇳🇦 `NAD` · 🇳🇬 `NGN` · 🇳🇴 `NOK` · 🇳🇵 `NPR` · 🇳🇿 `NZD` · 🇴🇲 `OMR` · 🇵🇪 `PEN` · 🇵🇭 `PHP` · 🇵🇰 `PKR` · 🇵🇱 `PLN` · 🇵🇾 `PYG` · 🇶🇦 `QAR` · 🇷🇴 `RON` · 🇷🇸 `RSD` · 🇷🇼 `RWF` · 🇸🇦 `SAR` · 🇸🇨 `SCR` · 🇸🇩 `SDG` · 🇸🇪 `SEK` · 🇸🇬 `SGD` · 🇸🇾 `SYP` · 🇸🇿 `SZL` · 🇹🇭 `THB` · 🇹🇯 `TJS` · 🇹🇲 `TMT` · 🇹🇳 `TND` · 🇹🇷 `TRY` · 🇹🇼 `TWD` · 🇹🇿 `TZS` · 🇺🇦 `UAH` · 🇺🇬 `UGX` · 🇺🇸 `USD` · 🇺🇾 `UYU` · 🇺🇿 `UZS` · 🇻🇪 `VES` · 🇻🇳 `VND` · `XAF` · `XCD` · `XOF` · `XPF` · 🇿🇦 `ZAR`

## 🏛️ Source

German customs sets the monthly exchange rates used to convert foreign-currency invoice amounts into euro when it determines the customs value of imported goods, which is also the basis for import VAT. The table covers about 30 ECB-quoted currencies at the common EU customs rate and about 90 further currencies.

- Publisher's own page: [Monthly exchange rates for customs value](https://www.zoll.de/DE/Fachthemen/Zoelle/Zollwert/Aktuelle-Wechselkurse/aktuelle-wechselkurse_node.html) · [www.zoll.de](https://www.zoll.de/)
- Publication: every month; the exact schedule, freshness status and any current delay are on the [German Customs (Zoll) rates page](https://allratestoday.com/tax-authority-rates-api/zollde/)
- Values are stored unmodified, with the publisher's own `rate_date` on every row — see the [methodology](https://allratestoday.com/official-rates-methodology/)

## 🧭 Reading the numbers

- `value` is always **quote currency per 1 unit of base currency** (`base: "EUR", quote: "USD", value: 1.15` means 1 EUR = 1.15 USD).
- German Customs (Zoll) quotes **foreign currency per 1 EUR** (e.g. `base: "EUR", quote: "USD"` means USD per one EUR).
- Need the other way round? Ask `getRate(target, source)` and the API inverts or crosses for you, flagged `derived: true` — never divide a published rate yourself in a compliance workflow.
- `rate_type` tells you which of the tax authority's series a row belongs to (`monthly` here); some publishers print buy/sell or several fixings for the same pair.

## 🧩 ERP & accounting systems

Loading the official German Customs (Zoll) rate into an accounting system is a supported workflow, not a hack. Step-by-step guides with the direction each system expects:

- [Dynamics 365 Business Central](https://allratestoday.com/docs/integrations/business-central/) — built-in Currency Exchange Rate Service, no code
- [Xero](https://allratestoday.com/docs/integrations/xero/) · [QuickBooks Online](https://allratestoday.com/docs/integrations/quickbooks/) · [SAP S/4HANA and ECC](https://allratestoday.com/docs/integrations/sap/) · [Odoo](https://allratestoday.com/docs/integrations/odoo/)

The same keyed endpoints return `?format=csv`, `?format=xml` and `?format=xlsx`, and accept the key as `?api_key=` on the URL for importers that cannot send headers:

```bash
curl "https://allratestoday.com/api/v1/central-bank/zollde/latest?format=xml&api_key=art_live_..."
```

## 🤖 AI agents

- MCP server: `npx -y @allratestoday/central-bank-mcp` (stdio) or the hosted endpoint `https://allratestoday.com/api/mcp` — tools for official rates, history, cross-bank comparison and publication calendars
- Already using the general SDK or MCP server? Since 2026-10-01 [`@allratestoday/sdk`](https://www.npmjs.com/package/@allratestoday/sdk) 1.4+ has `officialRates('zollde')` and [`@allratestoday/mcp-server`](https://www.npmjs.com/package/@allratestoday/mcp-server) 0.6+ has a `get_official_rates` tool — both return this source's latest table with no key, so you can add it without a second dependency
- Claude Code plugin (no key): `/plugin marketplace add AllRates-Today/claude-code-plugin` then `/plugin install allratestoday@allratestoday` — bundles both MCP servers plus an `/official-rate zollde ...` command
- Evaluating? Agents can self-issue a trial key with no signup: `POST https://allratestoday.com/api/agent/keys` (send `Content-Type: application/json`) returns a 100-call key valid 7 days that covers the free-plan methods (latest table, pairs); dated tables and history need a [paid plan](https://allratestoday.com/pricing/). The MCP servers expose it as `request_trial_key`
- Machine-readable site guide: [llms.txt](https://allratestoday.com/llms.txt) · [for-ai-agents](https://allratestoday.com/for-ai-agents/)

## ⚖️ Official vs derived rates

If German Customs (Zoll) does not print a pair directly, the API resolves it from the tax authority's own table and says so — official and computed values are never confused:

| `method` | `derived` | Meaning |
| --- | --- | --- |
| `published` | `false` | The tax authority printed this pair directly |
| `inverse` | `true` | Computed as 1 ÷ the published opposite direction |
| `cross` | `true` | Computed via EUR from two published rates |

## 🛡️ Error handling

Errors are thrown as `Error` with `status` (HTTP code) and `body` (the API's JSON error) attached:

```js
try {
  const pair = await getRate('USD', 'XXX', { apiKey: 'art_live_...' });
} catch (err) {
  console.log(err.message); // human-readable reason
  console.log(err.status);  // e.g. 404
}
```

| Status | Meaning |
| ------ | ------- |
| — | Missing `apiKey` (thrown before any request) |
| `400` | Malformed date or parameters |
| `401` | Invalid API key |
| `403` | Endpoint needs a [paid plan](https://allratestoday.com/pricing/) (historical dates & series) |
| `404` | Pair or date range not covered by German Customs (Zoll) |
| `429` | Monthly quota exceeded |

## 🔷 TypeScript

Full definitions ship with the package — no `@types` install:

```ts
import type { LatestRates, PairRate, DatedRates, RateEntry, HistoryQuery, RequestOptions } from 'zollde-exchange-rate';
```

## 📦 CommonJS

```javascript
const { getRate } = require('zollde-exchange-rate');

getRate('USD', 'EUR', { apiKey: 'art_live_...' }).then((pair) => console.log(pair.rate));
```

## 💡 Quota tips

- Rates change once a month — cache the official table locally and a small monthly quota goes a long way.
- Every request counts toward your AllRatesToday quota, shared across all AllRatesToday endpoints on your key.

## 📖 Methods reference

| Method | Plan | Description |
| ------ | ---- | ----------- |
| `getRate(source, target, { apiKey })` | Free | Latest rate for one pair, resolved from the official table |
| `getLatestRates({ apiKey })` | Free | The tax authority's full latest official table |
| `getRatesForDate(date, { apiKey, source?, target? })` | Paid | The official table (or one pair) for a YYYY-MM-DD date |
| `getHistory({ symbol \| source+target, from?, to? }, { apiKey })` | Paid | Daily series since 2004 |

## 📥 Bulk data (no key)

Need the whole archive rather than an API call? The same official tables are mirrored daily as open data:

- Hugging Face: [AllRatesToday/central-bank-exchange-rates](https://huggingface.co/datasets/AllRatesToday/central-bank-exchange-rates) — one CSV per institution (`rates/zollde.csv`)
- Kaggle: [allratestoday/central-bank-exchange-rates](https://www.kaggle.com/datasets/allratestoday/central-bank-exchange-rates)
- Raw JSON on GitHub: `https://raw.githubusercontent.com/AllRates-Today/central-bank-exchange-rates/main/data/zollde/latest.json`

## 🔗 Links

- **Website:** [allratestoday.com](https://allratestoday.com)
- [German Customs (Zoll) rates page](https://allratestoday.com/tax-authority-rates-api/zollde/) — live table, publication cadence, FAQ
- [All tax authority sources](https://allratestoday.com/tax-authority-rates-api/) · [Full list of 120+ central banks and 50+ tax authorities](https://allratestoday.com/central-bank-rates-api/institutions/) — one API, the same response shape for every source
- [Download central bank rates](https://allratestoday.com/download-central-bank-rates/) — every bank's latest table and history as Excel, CSV or JSON
- [Bank Exchange Rate API](https://allratestoday.com/bank-exchange-rate-api/) — live buy and sell rates from 1,200+ commercial banks in 120+ countries · [npm](https://www.npmjs.com/package/bank-exchange-rates) · [GitHub](https://github.com/AllRates-Today/bank-exchange-rates)
- [Package docs on the site](https://allratestoday.com/docs/sdk/zollde-exchange-rate/) · [ERP integration guides](https://allratestoday.com/docs/integrations/)
- [API documentation](https://allratestoday.com/docs/#central-bank) · [Interactive reference](https://allratestoday.com/api-reference/) · [Methodology](https://allratestoday.com/official-rates-methodology/)
- [Register (Free)](https://allratestoday.com/register) · [Dashboard](https://allratestoday.com/profile) · [Pricing](https://allratestoday.com/pricing/)
- [Status](https://allratestoday.com/status)
- [Postman collection](https://allratestoday.com/postman/)
- [ChatGPT app](https://chatgpt.com/plugins/plugin_asdk_app_6ae1e76098f48191a285ac3f5ab7a83b) — ask ChatGPT for live and official central bank rates
- [OpenAPI reference on Bump.sh](https://bump.sh/allratestoday/doc/allratestoday-api) — also on [SwaggerHub](https://app.swaggerhub.com/apis-docs/allratestoday/allratestoday-exchange-rate-central-bank-rates-api/2.2.0)
- [GitHub](https://github.com/AllRates-Today/zollde-exchange-rate)

## 📜 License

MIT
