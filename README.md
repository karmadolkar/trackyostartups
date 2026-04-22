# TrackYoStartups

**TrackYoStartups** is a venture capital portfolio analytics dashboard that evaluates startup performance using key SaaS and venture metrics.


---

## Overview

Venture capital firms track dozens of metrics across their portfolio companies. TrackYoStartups aggregates these metrics and calculates to quickly identify which companies are performing well and which may require attention.

---

## Features

* Simulate startup portfolio data
* Compute key venture and SaaS metrics
* Display leaderboard of portfolio companies
* Built with Anvil

---

## Metrics Used

The scoring system incorporates several common venture capital metrics.

Revenue Growth, Gross Margin, Burn Rate, Runway, CAC, LTV, LTV/CAC Ratio, NRR

## Startup Score

TrackYoStartups calculates a composite **valuation score** based on weighted metrics:

* Growth rate
* Net revenue retention
* LTV/CAC ratio
* Runway
* Gross margin


## Tech Stack

* Python
* Anvil (full-stack Python web framework)
* Anvil Data Tables

## Example Output

| Startup    | Growth | Runway | LTV/CAC | Score |
| ---------- | ------ | ------ | ------- | ----- |
| jhgjhhfgj  | 0.21   | 18.2   | 4.1     | 84    |
| gygcjykuy  | 0.18   | 15.7   | 3.8     | 69    |
| jcyjdtjkpg | 0.16   | 20.4   | 3.5     | 53    |


---

## License

MIT License
