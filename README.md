# Statistical Data Quality Checks

Applying probability and statistics to **data quality monitoring and data governance**, using real public data from New York City's 311 service requests.

## Why this project

Most data quality checks are simple rules: "this field can't be empty", "this date must be in the past".
Rules catch obvious errors, but they don't answer questions like:

- *Is today's record volume unusually low, or just normal variation?*
- *Are tickets taking longer to close than expected?*
- *If I audit a sample of 200 records, how confident can I be about the error rate of the whole table?*

These are statistical questions. This project builds data quality checks grounded in probability distributions and statistical inference.

## Dataset

[NYC 311 Service Requests from 2020 to Present](https://data.cityofnewyork.us/Social-Services/311-Service-Requests-from-2020-to-Present/erm2-nwe9) — NYC Open Data, accessed via the Socrata API.
Data is downloaded one month at a time and is not stored in this repository.

## Roadmap

| # | Notebook | Statistical concepts | Status |
|---|----------|----------------------|--------|
| 01 | Data profiling & quality scorecard | Descriptive statistics, completeness, uniqueness, validity, consistency | In progress |
| 02 | Volume monitoring | Poisson / normal distribution, Z-score, control charts | Planned |
| 03 | SLA & resolution time | Exponential distribution | Planned |
| 04 | Sample-based auditing | Binomial / hypergeometric distribution | Planned |
| 05 | Confidence intervals for quality rates | Statistical inference | Planned |
| 06 | Detecting profile changes | Chi-square test | Planned |
| — | Power BI quality dashboard | Scorecard visualization | Planned |

## Tools

Python (pandas, NumPy, SciPy, matplotlib) · Jupyter Notebook · Power BI

## About me

I'm Aline, a data professional working with data since 2020, specialized in Power BI, data modeling and report documentation.
This project is part of my study of probability and statistics (ProbEst – ICMC/USP).

[LinkedIn](https://www.linkedin.com/in/alinepaz)
