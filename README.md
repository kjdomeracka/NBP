# Polish Payments Market Dashboard (NBP data)

Interactive dashboard of the Polish payments market, built on National Bank of Poland (NBP) statistics for Q1 2024 – Q4 2025.

**Live demo:** _add your GitHub Pages link here_

## What's inside

- **Helicopter view**: cash vs. cashless, card and BLIK volumes, channel mix
- **Terminale POS**: terminal base, terminal types, card types, DCC and foreign cards
- **E-Commerce**: online payments, BLIK seasonality and average ticket per channel
- **SoftPOS**: market size, brand concentration, app store ratings and downloads

## Data sources

- [NBP – payment system statistics](https://nbp.pl)
- [Cashless.pl](https://www.cashless.pl) – SoftPOS terminal counts
- Google Play / App Store – SoftPOS app ratings and downloads (manually collected)

## Tools

| Tool | Used for |
|---|---|
| **Google Sheets** | Cleaning and flattening raw NBP tables into one master dataset |
| **[Claude](https://claude.ai) (Anthropic)** | AI assistant for building the code, auditing data against the source and iterating on UI/UX |
| **HTML / CSS / vanilla JavaScript** | The dashboard itself: a single self-contained file with no build step and no backend |
| **[Chart.js](https://www.chartjs.org/)** | Interactive charts |
| **GitHub Pages** | Hosting |

Responsive down to mobile.

## Author

Product Manager · FinTech & Payments
