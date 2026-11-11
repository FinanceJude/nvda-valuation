# NVIDIA (NVDA) Valuation

**Jude Solis**, B.S. Business Administration, Finance, California Lutheran University (2026)

Priced as of Nov 9, 2026.

**Files:** [Excel model](NVDA%20DCF%20MODEL.xlsx) | [One-page write-up (PDF)](NVDA_Valuation_Writeup-3.pdf)

| | |
|---|---|
| DCF intrinsic value (Base) | **$215.60** |
| Close, Nov 9, 2026 | $178.67 |
| Upside / rating | +20.7%, Buy |
| Perpetuity cross-check | $188.71 |
| Bear / Bull | $126.53 / $294.24 |

## Approach

I built a five-year integrated three-statement model from the FY2022–FY2026 10-Ks. Every historical year ties to the reported totals, and the balance sheet balances in every projected year. I valued Nvidia with an exit-multiple DCF, checked it against a perpetuity-growth method and trading comps, and stress-tested it with sensitivity tables. One switch moves the model between Bear, Base and Bull cases.

## Revenue growth: 85% / 30% / 15% / 10% / 6% (FY27–FY31)

- FY27 rests on reported results. H1 actual revenue was $177.8bn, Q3 guidance is $108.0bn, and I assume about $114bn in Q4, so FY27 comes to about $399bn (+85%).
- Growth slows quickly after FY27. Revenue is already about 8x FY2023. The main risks are hyperscalers pausing capex, custom chips (ASICs) taking share, and China export limits. The Q3 guide assumes no China data center revenue. Growth averages about 15% a year from FY27 to FY31.
- Bear (75% / 10% / 0% / 3% / 3%) assumes a spending pause and share lost to ASICs. Bull (90% / 45% / 25% / 15% / 10%) assumes the Rubin product cycle keeps growing.

## Margins and costs

- Gross margin starts at 74%, matching the Q3 guide, and drifts down 50bp a year to 72% as competition and new products weigh on pricing. Bear ends at 65%, Bull at 74%.
- R&D goes from 7.5% to 8.5% of revenue and SG&A from 1.5% to 1.9%, starting from H1 FY27 levels. These creep up because costs keep growing as revenue growth slows.
- Tax rate is 17%, the midpoint of guidance.

## Cash flow and balance sheet

- Capex is 2.5% of revenue, matching H1 FY27. D&A rises from 1.3% to 1.7% of revenue.
- Working capital: receivables at 65 days and payables at 57 days, both flat with FY26. Inventory days ease from 125 to 110 as supply catches up.
- Buybacks are 60% of free cash flow, slightly above the FY24–FY26 average of about 54%. The diluted share count falls 1% a year.
- Dividends: $0.25 a quarter today ($1.00 a year), growing to $1.30 a year by FY31.
- Debt: the $25bn of notes issued in June 2026 is included.

## Valuation

- WACC through FY31 is 13.9%. CAPM inputs: a 4.88% 10-year Treasury yield, a 5% equity risk premium, and a beta of 1.81 (2.21 raw, adjusted toward 1). Cash flows are discounted mid-year, and FY27 counts only cash flow after the July 2026 balance sheet, because earlier cash is already in the $23bn net cash.
- Terminal value: 16.5x FY31 EBITDA. That's in line with Nvidia's current multiple and well below the 33.8x peer median, since growth will have slowed to 6% by then. Nvidia's risk should fall as it matures, so I check the terminal value at a terminal WACC of 9.8% (beta 1.0). At that rate, 16.5x implies 4.9% perpetual growth, roughly nominal GDP.
- Perpetuity cross-check at 4.0% growth gives $188.71. The Buy case holds under both methods, but the margin over the share price is thinner (+6%) without the exit multiple.

### Scenario output ($ per share)

| Case | DCF value | Upside / (downside) | Perpetuity value |
|---|---:|---:|---:|
| Bear | 126.53 | (29.2%) | 111.25 |
| **Base** | **215.60** | **20.7%** | **188.71** |
| Bull | 294.24 | 64.7% | 255.70 |

### Sensitivity: WACC vs. exit EV/EBITDA multiple ($ per share)

| WACC \ Multiple | 12.5x | 14.5x | 16.5x | 18.5x | 20.5x |
|---|---:|---:|---:|---:|---:|
| 11.9% | 185.36 | 207.97 | 230.57 | 253.18 | 275.78 |
| 12.9% | 179.38 | 201.15 | 222.92 | 244.69 | 266.46 |
| 13.9% | 173.66 | 194.63 | **215.60** | 236.58 | 257.55 |
| 14.9% | 168.18 | 188.40 | 208.61 | 228.82 | 249.03 |
| 15.9% | 162.95 | 182.43 | 201.91 | 221.40 | 240.88 |

## Comps

Using run-rate multiples, the peer median for AMD, Broadcom, Qualcomm and Marvell implies about $275, so the DCF sits 21.5% below it. Nvidia trades at about 16.6x EV/EBITDA against a peer median of 33.8x, which suggests the market already expects its growth to slow.

## Sensitivities and risks

- Terminal value is 81% of enterprise value, and each turn of exit multiple moves the value by about $10.50.
- A 5-point change in annual growth moves the value by about $35, and a 4-point change in gross margin by about $14.
- Key risks are export controls, customer concentration and custom-chip competition.

## Limitations

- Market inputs (prices, beta, Treasury yield) come from secondary sources and need refreshing. Marvell's price is from Nov 5.
- TSMC was excluded from the comps because its release doesn't disclose D&A or debt.
- The terminal value still dominates the valuation, which is why I show the exit-multiple and perpetuity methods side by side.
- The model will be refreshed after Nvidia's Q3 report on Nov 17.
