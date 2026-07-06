<div align="center">

<img src="assets/hero.svg" width="100%" alt="Sumit Prajapat — Data Analyst · BI Developer · PL-300 Certified"/>

<br/><br/>

<a href="https://www.linkedin.com/in/sumit-k-prajapat/"><img src="https://img.shields.io/badge/LinkedIn-connect-3FB950?style=flat-square&labelColor=0D1117&logo=linkedin&logoColor=3FB950"/></a>
&nbsp;<a href="mailto:sumitkprajapat29@gmail.com"><img src="https://img.shields.io/badge/Email-sumitkprajapat29@gmail.com-E0B341?style=flat-square&labelColor=0D1117&logo=gmail&logoColor=E0B341"/></a>
&nbsp;<a href="https://skpkush.github.io/Sumit_analystics/"><img src="https://img.shields.io/badge/Portfolio-live-58A6FF?style=flat-square&labelColor=0D1117&logo=github&logoColor=58A6FF"/></a>

</div>

<br/>

```sql
sumit_prajapat=# SELECT * FROM about WHERE honest = true;
```

I take data the whole way: **ingestion → Azure pipelines → SQL star schemas → Power BI dashboards → ML models** — and I lead every dashboard with **one quantified headline**, not a wall of charts.

**2+ years inside BFSI** selling and servicing insurance products *before* analyzing them — now a freelance Data Analyst with **Finonus Capital**. B.Com graduate, **Microsoft (PL-300 · AZ-900 · DP-900) and AWS certified**.

> `-- The kind of analyst who measures e-commerce retention on customer_unique_id — the real person —`
> `-- and flags a dataset cut-off artifact before anyone misreads it as a downturn.`

**Domains** <kbd>Finance & Insurance</kbd> <kbd>Healthcare</kbd> <kbd>E-Commerce</kbd> &nbsp;·&nbsp; **Seeking** <kbd>Data Analyst</kbd> <kbd>BI Developer</kbd> <kbd>Power BI Developer</kbd>

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# EXPLAIN ANALYZE how_i_ship;
```

<div align="center">
</div>

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# SELECT project, headline_metric
sumit_prajapat-# FROM   featured_work
sumit_prajapat-# ORDER  BY impact DESC;
```

| `#`  | `project`                             | `headline_metric`                                  |
| :--- | :------------------------------------ | :------------------------------------------------- |
| `01` | Healthcare Insurance Claims Analytics | 558,211 claims → **226× fraud concentration**      |
| `02` | Mutual Fund Analytics Platform        | **9M+ NAV rows** · 10,571 funds · 51 AMCs          |
| `03` | Olist E-Commerce Analytics            | 112,650 records → **~97% one-time buyers** exposed |
| `04` | Customer Segmentation Engine          | RFM + 3 models · **Silhouette 0.52** · live app    |

`(4 rows)`

```sql
sumit_prajapat=# \x on   -- expanded display: full detail per project
```

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics"><code>[01]</code> Healthcare Insurance Claims Analytics</a></h3>
      <p><b>558,211 Medicare claims → 226× fraud concentration finding</b></p>
      <p><sub>Azure Data Factory ingestion → PostgreSQL 9-table warehouse → scikit-learn fraud model (<b>90.1% recall · AUC 0.9573</b>) → 4-page executive Power BI report.</sub></p>
      <p><code>-- impact: $295.68M claim exposure flagged; 90.1% of fraud cases caught</code></p>
      <p><kbd>Azure ADF</kbd> <kbd>PostgreSQL</kbd> <kbd>scikit-learn</kbd> <kbd>Power BI</kbd></p>
      <p><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics"><code>→ view repo</code></a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/mf-analytics-platform"><code>[02]</code> Mutual Fund Analytics Platform</a></h3>
      <p><b>9M+ NAV rows · 10,571 funds · 51 AMCs</b></p>
      <p><sub>Production-grade 5-dimension / 4-fact star schema · full risk suite (Sharpe, Sortino, alpha/beta, drawdown) · Prophet 30/60/90-day NAV forecasts · Streamlit front-end.</sub></p>
      <p><code>-- impact: 10,571 funds across 51 AMCs made comparable on one risk framework</code></p>
      <p><kbd>Star Schema</kbd> <kbd>Python</kbd> <kbd>Prophet</kbd> <kbd>Streamlit</kbd></p>
      <p><a href="https://github.com/Skpkush/mf-analytics-platform"><code>→ view repo</code></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard"><code>[03]</code> Olist E-Commerce Analytics</a></h3>
      <p><b>112,650-record warehouse · 40+ DAX measures</b></p>
      <p><sub>Uncovered <b>~97% one-time buyers</b> by measuring retention on the correct customer grain (<code>customer_unique_id</code>) · AI visuals · what-if price simulation.</sub></p>
      <p><code>-- impact: retention corrected from order grain to customer grain across 99,441 orders</code></p>
      <p><kbd>Power BI</kbd> <kbd>DAX</kbd> <kbd>SQL</kbd> <kbd>Power Query</kbd></p>
      <p><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard"><code>→ view repo</code></a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Customer-Segmentation"><code>[04]</code> Customer Segmentation Engine</a></h3>
      <p><b>RFM + 3 clustering models · Silhouette 0.52</b></p>
      <p><sub>K-Means vs Hierarchical vs DBSCAN benchmarked head-to-head · CLV estimation · cohort analysis · deployed as an interactive app.</sub></p>
      <p><code>-- impact: 4 actionable customer segments with CLV, deployed live for stakeholders</code></p>
      <p><kbd>Python</kbd> <kbd>scikit-learn</kbd> <kbd>Pandas</kbd> <kbd>Streamlit</kbd></p>
      <p><a href="https://github.com/Skpkush/Customer-Segmentation"><code>→ view repo</code></a> &nbsp; <a href="https://customer-segmentation-g4vjra3jvttxstxguxhnff.streamlit.app/"><code>🟢 live demo</code></a></p>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# SELECT category, tools FROM toolkit GROUP BY category;
```

| `category`         | `tools`                                                                                                     |
| :----------------- | :---------------------------------------------------------------------------------------------------------- |
| `business_intel`   | <kbd>Power BI</kbd> <kbd>DAX</kbd> <kbd>Power Query</kbd> <kbd>Excel</kbd>                                    |
| `data_engineering` | <kbd>SQL</kbd> <kbd>PostgreSQL</kbd> <kbd>Azure Data Factory</kbd> <kbd>Star Schema</kbd> <kbd>ETL</kbd>      |
| `python_ml`        | <kbd>Python</kbd> <kbd>Pandas</kbd> <kbd>NumPy</kbd> <kbd>scikit-learn</kbd> <kbd>Prophet</kbd> <kbd>Streamlit</kbd> |
| `cloud_and_ops`    | <kbd>Microsoft Azure</kbd> <kbd>AWS</kbd> <kbd>Git</kbd> <kbd>Jupyter</kbd>                                   |

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# SELECT * FROM certifications WHERE verified = true;
```

| `credential`                    | `issuer`      | `status`                                                                                                     |
| :------------------------------ | :------------ | :------------------------------------------------------------------------------------------------------------ |
| ★ **PL-300** · Power BI Data Analyst Associate | Microsoft     | [`→ verify`](https://learn.microsoft.com/en-us/credentials/certifications/data-analyst-associate/)             |
| **AZ-900** · Azure Fundamentals              | Microsoft     | [`→ verify`](https://learn.microsoft.com/en-us/credentials/certifications/azure-fundamentals/)                 |
| **DP-900** · Azure Data Fundamentals         | Microsoft     | [`→ verify`](https://learn.microsoft.com/en-us/credentials/certifications/azure-data-fundamentals/)            |
| **Cloud Practitioner**                       | AWS           | [`→ verify`](https://aws.amazon.com/certification/certified-cloud-practitioner/)                               |
| **Investment Foundations**                   | CFA Institute | [`→ verify`](https://www.cfainstitute.org/en/programs/investment-foundations)                                  |
| **SQL Certified**                            | HackerRank    | [`→ verify`](https://www.hackerrank.com/certificates/)                                                         |

<img src="assets/divider.svg" width="100%"/>

<div align="center">

<img src="assets/footer.svg" width="100%" alt="COMMIT; — open to Data Analyst and BI Developer roles — sumitkprajapat29@gmail.com"/>

</div>
