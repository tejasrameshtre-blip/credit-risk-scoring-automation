# Credit Risk Scoring Automation

Automated borrower credit risk scoring system built in n8n.

## What it does
- Accepts borrower applications via a live form
- Scores each borrower using the 5 Cs of Credit framework
- Outputs a LOW / MEDIUM / HIGH risk rating automatically
- Logs all submissions to a Google Sheets dashboard
- Sends email alerts only for HIGH risk cases

## The 5 Cs Framework
| C | Factor | What it measures |
|---|---|---|
| C1 | Capacity | Loan-to-income ratio |
| C2 | Capital | Savings vs loan amount |
| C3 | Collateral | Security offered |
| C4 | Conditions | Loan purpose |
| C5 | Character | Previous defaults |

## Risk Rating Thresholds
- Score 75+ = LOW risk
- Score 45–74 = MEDIUM risk
- Score below 45 = HIGH risk (email alert triggered)

## Tools Used
- n8n (workflow automation)
- Google Sheets (portfolio dashboard)
- Gmail (HIGH risk alerts)


