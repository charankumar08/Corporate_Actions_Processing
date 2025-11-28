# Corporate Actions Processing Simulation – Capital Markets Operations

## 📌 Project Overview
This project simulates how different corporate actions impact the Security Master and portfolio valuation in the capital markets domain.  
It demonstrates a full back-office workflow from receiving corporate action notifications to updating the final MIS for stakeholders.

## 🎯 Objective
To apply corporate action rules (split, bonus, dividend, rights issue, reverse split, name change, merger) on a live equity portfolio and generate accurate post-action positions using an audit-friendly MIS format.

## 🛠 Key Activities Performed
- Built a 20-security equity portfolio (India + US)
- Created corporate action bulletins for each security
- Applied the impact of each event on:
  - Shares outstanding
  - Market price
  - Total portfolio valuation
- Updated ticker and security name where required (reference-data change)
- Reconciled Before vs After portfolio values
- Prepared presentation for reporting to stakeholders

## 📂 Files in this Repository
| File | Description |
|------|-------------|
| `Corporate Actions.xlsx` | Full MIS dataset including Before & After positions, corporate action rules and updated portfolio |
| `Corporate Actions Processing Simulation – Capital Markets Operations.pptx` | Executive-style PPT summarizing project findings and insights |

## 🧠 Concepts Demonstrated
- Corporate Actions Domain Knowledge:
  * Stock Split (2:1), Bonus Issue (1:1), Reverse Split (5:1)
  * Dividend Distribution, Rights Issue, Name Change
  * Merger (Netflix absorbed into JPMorgan)
- Security Master Maintenance
- Portfolio Valuation & Reconciliation
- MIS Reporting Format for Capital Markets Operations

## 🧰 Tools Used
| Tool | Purpose |
|------|---------|
| Microsoft Excel | Corporate action processing, valuation calculations, MIS formatting |
| PowerPoint | Management reporting and summary deck |

## 📌 Outcome
Processed and reconciled the impact of 10+ corporate action types on a global equity portfolio, delivering a clean and accurate MIS file — matching the expectations of Investment Banking Operations and Capital Markets back-office teams.

---

🚀 **Next Steps (Future Enhancements)**
- Automate corporate action processing through Excel scripting
- Add Bloomberg/Reuters identifiers (CUSIP / SEDOL / RIC)
- Introduce impact on settlement cycles and cash flows
