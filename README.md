# Yasin Latif

Economics @ Princeton '29. Public-equity research: earnings reactions, valuation, and risk.

## Research

### [Earnings reactions in payments stocks: an event study](https://github.com/yasinlatif22-cpu/payments-earnings-event-study)

Python event study of 150 earnings releases across Visa, Mastercard, AXP, PYPL, FIS and GPN, using market-model abnormal returns. Hypotheses were written before testing.

- Earnings days move these stocks roughly 2 to 6 times more than normal days (p ≤ 0.002 in all six).
- Neither EPS surprise nor the prior 60-day run-up predicted the direction of the reaction.
- Visa's 8.8-point one-year lead over Mastercard is ordinary for the pair, about 0.6 to 0.7 standard deviations of tracking error.
- Both stocks' beta to the S&P 500 fell from roughly 1.1 to 1.3 in 2019-21 to about 0.25 in 2026. I have not tested why.
- 36 p-values reported; the one below 0.05 has the wrong sign and is not treated as a finding.

<img src="https://raw.githubusercontent.com/yasinlatif22-cpu/payments-earnings-event-study/main/outputs/rolling_beta.png" width="600" alt="Rolling 126-day beta of Visa and Mastercard vs SPY, 2019-2026">

## Valuation models

### [Visa (V) discounted cash flow](https://github.com/yasinlatif22-cpu/financial-models) (work in progress)

- Base case implies $278 per share (3.0% perpetuity growth) to $343 (18x FY2030E EBITDA exit multiple) against a $360.66 market price on 10/2/2026. WACC of 8.94%.
- Known issues and planned fixes (sourcing, exit multiple, reverse DCF, scenarios) are listed in the repo.

**Currently working on:** an LBO model of Bath & Body Works (BBWI).

Python · Excel · Bloomberg · Capital IQ · Preqin

[LinkedIn](https://linkedin.com/in/yasinlatif) · yasinlatif22@gmail.com
