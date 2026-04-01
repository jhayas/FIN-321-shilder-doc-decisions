Created by: FX Hedging Team
Updated by: jhayaas
Date Created: 2026-03-31
Date Updated: 2026-03-31
Version: 1.0 | LLM Used: Claude
To: Adam Stauffer

# Executive Summary (142 words)

Our firm faces a significant EUR 11.47 million receivable due in one year from a major European client engagement. Based on a €12.5M USD equivalent exposure and current EURUSD spot rate of 1.0875, currency volatility presents material downside risk to our USD proceeds. A 10% depreciation of the euro would reduce our receivable value by approximately $1.25 million. This memo outlines three hedging families—forwards, protective puts, and risk reversals—each with distinct cost-benefit profiles. We recommend proceeding to Stage 2 to quantify expected outcomes under multiple FX scenarios and determine the optimal hedge for our risk tolerance and cost constraints.

## Background & Objectives

Our Technology Services division has contracted to deliver €12.5 million in services over the next 12 months, with payment due in one year. This represents approximately 8% of annual revenue and creates meaningful FX exposure. The objective is to protect USD cash flows from adverse EURUSD movements while maintaining upside potential if the euro appreciates.

## Methods

We will evaluate three hedging strategies:

1. **Forward Contract (1.0910 rate)**: Locks in future USD proceeds at ~$13.64M with zero upfront cost; eliminates both upside and downside.
   - *Pros*: Certainty, no premium cost
   - *Cons*: No flexibility, foregoes appreciation gains

2. **Protective Put (K = 1.0875, premium $0.017/unit)**: Caps downside at ~$12.35M while allowing upside participation if EUR strengthens.
   - *Pros*: Downside protection with upside potential
   - *Cons*: Premium cost (~$212,500) reduces net proceeds

3. **Risk Reversal (Long Put + Short Call)**: Reduces hedge cost by selling call option, offsetting put premium.
   - *Pros*: Minimal net cost (~$62,500)
   - *Cons*: Caps upside at 1.10, requires active management

## Limitations & Next Steps

Current analysis assumes stable interest rates and no credit counterparty risk. Stage 2 will build an Excel model comparing payoff profiles across spot rates ranging from 0.95 to 1.15. Stage 3 will document technical specifications for scalability. Stage 4 will deliver final recommendation with sensitivity analysis and board-ready presentation materials.

## References

- Bloomberg FX rates (as of 2026-03-31)
- Stage 1 Memo Assignment Guidelines
- Scenario 3 Parameters (EUR Receivable, 1-Year Horizon)