# Deeksha Moole
**Dallas, TX** · m.deekshareddy1208@gmail.com · [linkedin.com/in/deekshamoole](https://linkedin.com/in/deekshamoole)

Data & BI engineer with four years building analytics infrastructure — ETL pipelines, cloud data warehouses, and dashboards that turn raw operational data into decisions. 


---

## Projects

### [Air Quality Reporting Pipeline](https://github.com/deekshamoole98/Air_Quality)
`Python` `Lambda` `Glue` `S3` `Athena` `QuickSight`

Pulls PM2.5 readings from the OpenAQ API, cleans them (sentinel filtering, outlier flagging, schema validation), and lands curated Parquet in S3 for Athena querying. Lambda + Glue + EventBridge on the AWS side; 22 unit tests, no AWS account needed to run locally. Produces daily averages, WHO guideline breach rates, and week-over-week trends by city.

### [GitHub Watchtower](https://github.com/deekshamoole98/github-watchtower)
`Python` `Lambda` `S3` `Athena` `SNS` `EventBridge`

Captures the public GitHub event stream on a schedule, stores date-partitioned NDJSON in S3, and runs four data quality checks on every ingestion run: freshness, duplicate IDs, per-field schema completeness rate, and day-over-day volume comparison. Four Athena views surface event type distribution, most active repos, hourly activity patterns, and volume trend.

---

## Skills

| | |
|---|---|
| **Query & Warehouse** | SQL · Snowflake · Redshift · Athena · dbt · Spark SQL |
| **ETL & Pipeline** | Python · AWS Glue · Lambda · Alteryx · Airflow |
| **BI & Visualization** | Tableau · Power BI · QuickSight · Excel |
| **Cloud & Infra** | AWS (S3, Glue, Athena, Lambda, Redshift) · Azure Synapse |

---

## Publication

**Classification of Brain Tumor and its types using Convolutional Neural Network**  
K N Deeksha · **Deeksha M** · Anagha V Girish · Anusha S Bhat · Lakshmi H  
*IEEE, 2020* · [View on IEEE Xplore](https://ieeexplore.ieee.org/document/9298306)

Applied convolutional neural networks to MRI scan classification, distinguishing tumor types across a multi-class dataset.

---

## Education

| Degree | School | Status |
|---|---|---|
| MS, Information Systems | UT Arlington | In progress |
| BE, Computer Science | Osmania University | 2021 |

<!--
**deekshamoole98/deekshamoole98** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
