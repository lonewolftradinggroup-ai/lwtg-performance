# LWTG Live Performance Dashboard

**Lone Wolf Trading Group 🐺 — MITS System Performance**

Live dashboard tracking closed trade results for the MITS (Multi-Indicator Trading System) and QC Signals strategies across all active micro futures instruments.

🔗 **[View Dashboard](https://lonewolftradinggroup-ai.github.io/lwtg-performance)**

---

## What It Shows

- **Period P&L** — Net closed trade results across the active reporting window
- **Win Rate & Profit Factor** — Aggregate and per-instrument breakdown
- **MITS by Instrument** — MES, MNQ, MGC, M2K trade results
- **QCS by Preset** — QC Signals preset performance (MNQ-4m, MGC-5m, MES-5m, MNQ-5m)
- **Regime Alignment** — Aligned vs. counter-regime trade comparison (primary edge metric)

---

## Data Source

Performance data is sourced from the LWTG MITS Trading Log (Google Sheets) and updated periodically. All figures reflect **closed trades only** (TP, SL, EOD exits). Open positions are excluded.

> ⚠️ Gross P&L only — commission/fee accounting (~$1.90 round-trip per contract) not yet reflected.

---

## Instruments Traded

| Instrument | Timeframe | Strategy |
|---|---|---|
| MES | 5m | MITS |
| MNQ | 15m / 4m | MITS / QCS |
| MGC | 5m / 5m | MITS / QCS |
| M2K | 5m | MITS |

---

## Related Repos

| Repo | Description |
|---|---|
| [lwtg-mits-system](https://github.com/lonewolftradinggroup-ai/lwtg-mits-system) | System distribution hub — Pine scripts, GAS, User Guide |
| [lwtg-trade-manager](https://lonewolftradinggroup-ai.github.io/lwtg-trade-manager) | Active trade management app |
| [lwtg-journal](https://lonewolftradinggroup-ai.github.io/lwtg-journal) | Trade journal app |
| [lwtg-fund-manager](https://lonewolftradinggroup-ai.github.io/lwtg-fund-manager) | WRP Holdings capital fund tracker |

---

## Disclaimer

*Not financial advice. Past performance is not indicative of future results. MITS is a proprietary system developed for internal use by Lone Wolf Trading Group.*
