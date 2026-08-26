# Vaishali

Data analyst working with SQL, Python and cloud data tooling. Looking for remote data analyst or analytics engineering roles.

---

## Projects

**[nyc311-pipeline](https://github.com/vaishali0709/nyc311-pipeline)** — Daily pipeline pulling NYC 311 service requests from the Socrata API into BigQuery, modelled with dbt, 27 data tests, scheduled with GitHub Actions. Runs itself every morning. The README covers what I found in the data and two bugs that produced clean, green, wrong output.
`Python` `BigQuery` `dbt` `GitHub Actions`

**[campaign-lift-analysis](https://github.com/vaishali0709/campaign-lift-analysis)** — Did the marketing campaigns work? On real dunnhumby retail data the obvious comparison says spending went up 4.7x. It didn't — the retailer had picked its best customers, and they were already spending four times more before any campaign went out. Difference-in-differences gets to $527, then fails its own parallel trends check. The conclusion is that this data can't measure lift, and what can be measured instead.
`SQL` `MySQL` `matplotlib`

**[saas-retention-analysis](https://github.com/vaishali0709/saas-retention-analysis)** — Cohort retention and churn across 4,200 SaaS customers in MySQL. Churn varies sharply by acquisition channel — Paid Search at 67.9% against Referral at 33.3% — which changes what each channel is actually worth.
`SQL` `MySQL` `Window functions`

**[shopping-recommender-system](https://github.com/vaishali0709/shopping-recommender-system)** — Item-based collaborative filtering and SVD on retail transaction data, with a temporal train/test split and a popularity baseline to measure against. MAP@5 of 0.1244 versus 0.1053 for the baseline.
`Python` `pandas` `scikit-learn`

**[cryptopunks-sql-analysis](https://github.com/vaishali0709/cryptopunks-sql-analysis)** — Thirteen SQL queries on NFT trading data: price movement over time, holder concentration, and volume patterns.
`SQL` `MySQL`

---

## Tools

**Query** — SQL (BigQuery, MySQL, SQLite), window functions, CTEs, query tuning
**Transform** — dbt: models, tests, sources, macros, documentation
**Cloud** — BigQuery: partitioning, clustering, cost control, service accounts
**Python** — pandas, API ingestion, incremental loading
**Automation** — GitHub Actions, scheduled pipelines, secrets management

---

## Currently

Building out the cloud side of my work — orchestration, testing, and pipelines that keep running without me watching them.

📫 [LinkedIn](www.linkedin.com/in/vaishali-singh-73a2a5271)
