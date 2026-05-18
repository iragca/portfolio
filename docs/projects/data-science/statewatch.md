---
tags:
  - FastAPI
  - Analytics
  - Data Engineering
  - Dashboarding
  - PostgreSQL
---

<div style="display: flex;">


<div>
StateWatch is a simple data pipeline to gather financial data of multiple traded assets mainly Indexes, Commodities and Cryptocurrencies from multiple APIs and display on them on a dashboard. The chosen financial assets that I keep track of in this project are the main metrics that I follow for market signals. As such, this entire project is opinionated.
</div>
</div>

[Dashboard :material-web:](https://datastudio.google.com/reporting/5a683a41-92af-4ec0-9fb3-8b4fe1103c89){ .md-button }
[GitHub :simple-github:](https://github.com/iragca/statewatch){ .md-button }

=== "Dashboard"

    <img src="https://ustp.party/statewatch/dashboard.png">

## Methodology

- Use [coingecko](https://www.coingecko.com/), [ALPHA VANTAGE](https://www.alphavantage.co/), [Yahoo Finance](https://finance.yahoo.com/) APIs to aggregate data.
- FastAPI as the backend hosted for free on Vercel
- PostgreSQL database hosted for free on Supabase
- Google Data Studio for dashboarding
