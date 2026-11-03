# Polish Payments Market Dashboard (NBP data)

Interactive dashboard of the Polish payments market, built on National Bank of Poland (NBP) statistics for Q1 2024 – Q4 2025.

**Live demo:** _kjdomeracka.github.io/NBP/_


## Problem

The National Bank of Poland (NBP) publishes comprehensive quarterly statistics on the Polish payments market, yet in their raw form they offer limited analytical value.

**The data is spread across several Excel files, split into raw tables with inconsistent structures, and comes with no visual layer.**


## Goal

A **digestible, decision-oriented tool** that helps to:

- **Read the market at a glance**: quarterly trends and year-over-year changes
- **Spot behavioural shifts**: cash vs. cards vs. BLIK, in-store vs. online, and the rise of SoftPOS
- **Draw conclusions**: turn data into **opportunities** and input for **product and go-to-market strategy**


## Challenges

- **Fragmented data.** Inconsistent NBP tables consolidated in Google Sheets into one master dataset.
- **Gaps in official statistics.** NBP does not track SoftPOS separately, so the segment was built from Cashless.pl terminal counts and app store data, with like-for-like year-over-year growth.
- **Data accuracy.** An audit against the master dataset caught and fixed errors in totals, growth rates and foreign card figures.
- **Depth vs. readability.** Redundant charts removed, metrics grouped into compact KPI tiles, navigation and mobile layout added.


## What's inside

_The dashboard interface is in Polish. It is responsive and works on mobile._

- **Helicopter view**: channel mix (POS, e-commerce, ATM), cash vs. cashless, BLIK across channels (average ticket, weekly seasonality), merchants online vs. in-store, foreign cards and DCC potential
- **POS terminals**: acceptance infrastructure (merchants, terminals), payment methods by card type and BLIK, domestic vs. foreign cards, DCC potential, BLIK code vs. contactless
- **E-commerce**: payment method mix, average basket, card-not-present vs. BLIK online, merchants and online stores
- **SoftPOS**: market size and share of POS, brand concentration, terminal growth per brand (2022–2024), app downloads, ratings and iOS availability

Each tab closes with **product signals**: short takeaways that translate the numbers into opportunities.


## Data sources

- [NBP – payment system statistics](https://nbp.pl)
- Cashless.pl, Google Play, App Store


## Tools

| Tool | Used for |
|---|---|
| **Google Sheets** | Cleaning and flattening raw NBP tables into one master dataset |
| **Claude (Anthropic)** | AI assistant for building the code, auditing data against the source and iterating on UI/UX |
| **HTML / CSS / vanilla JavaScript** | The dashboard itself: a single self-contained file with no build step and no backend |
| **Chart.js** | Interactive charts |
| **GitHub Pages** | Hosting |


## Author

Katarzyna Domeracka · Senior Product Manager
