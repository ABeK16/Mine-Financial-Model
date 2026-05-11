
CC Mine — Investment Calculator
Overview
An interactive web-based investment analysis tool for a mining operation in Gilpin County, Colorado. The calculator models working interest (WI) returns based on phased production ramp-up, plasma milling technology, and multi-machine deployment.

https://abek16.github.io/Mine-Financial-Model/

Features
Investment Tiers
0.2% WI — $50,000

0.5% WI — $125,000

1.0% WI — $250,000

Production Scenarios
Scenario	Description
Conservative	Base case, traditional milling
Moderate	3-machine plasma steady state
Optimistic	Full capacity with supergene zone
Phase-Based Production Tracking
Check each phase manually when production targets are achieved:

Phase	Timeframe	Au (oz/day)	Ag (oz/day)
Install & Training	~May 25–31	0	0
1 Shift · Machine #1	~Jun 1–14	8	32
2 Shifts · Machine #1	~Jun 15–28	16	64
2 Shifts · Machines 1 & 2	~Jul 6–19	32	128
2 Shifts · All 3 Machines	~Jul 20 – Aug 2	48	192
Steady State — 3 Machines	Aug 3–31	48	192
Supergene Zone Mining	Aug 3 – Sep 30	72	245
Full Capacity Target	September+	100	300
Machine Checkboxes
Machine #1 — Enables first production shift (8 oz Au/day)

Machine #2 — Doubles output (32 oz Au/day)

Machine #3 — Steady state (48 oz Au/day)

Each machine must be manually checked when confirmed operational.

Adjustable Assumptions
Gold price ($2,500–5,000/oz)

Silver price ($20–90/oz)

Overhead ($300–900/oz Au)

Distribution percentage (70–95%)

Outputs
Key Metrics
Investment amount & working interest

Active phase production (Au + Ag oz/day)

Monthly distribution

Payback period (months from June 1)

Phase Breakdown Table
Displays per-phase:

Duration (days)

Production rates

Gross revenue

Your distribution

Cumulative P&L

Status (Done / Active / Pending)

12-Month Cumulative P&L Chart
Color-coded bars show:

Solid green/red — Confirmed phases (in profit / still recouping)

Faded green/red — Projected (not yet achieved)

Technology Stack
HTML5 / CSS3

Vanilla JavaScript

Chart.js 4.4.1 (visualization)

Data Sources
Culbert (1986)

Dahrouge Geological Consulting (2025)

Site visit verification (post-visit v2.0)

Usage Instructions
Select investment tier — Click 0.2%, 0.5%, or 1.0% WI button

Choose production scenario — Conservative / Moderate / Optimistic

Adjust price assumptions — Use sliders for gold, silver, overhead, distribution

Check machines when online — Machine #1, #2, #3 as they become operational

Check phases when targets achieved — Mark each production phase complete

Review outputs — Metrics update automatically; chart reflects confirmed vs projected

Important Notes
Not financial advice — For due diligence purposes only

Phase dates include operator timeline adjustments (+1.5 weeks)

Overhead is calculated per ounce of gold produced

Distribution percentage applies to net mine profit

Chart distinguishes between confirmed (checked phases) and projected (unchecked)

License
Proprietary — For internal due diligence and investor use only.
