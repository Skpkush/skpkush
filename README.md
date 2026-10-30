<div align="center">

<img src="assets/hero.svg" width="100%" alt="Sumit Prajapat — Data Analyst · BI Developer · PL-300 Certified"/>

<br/><br/>


<a href="https://www.linkedin.com/in/sumit-k-prajapat/"><img src="https://img.shields.io/badge/LinkedIn-connect-3FB950?style=flat-square&labelColor=0D1117&logo=linkedin&logoColor=3FB950"/></a>
&nbsp;<a href="mailto:sumitkprajapat29@gmail.com"><img src="https://img.shields.io/badge/Email-sumitkprajapat29@gmail.com-E0B341?style=flat-square&labelColor=0D1117&logo=gmail&logoColor=E0B341"/></a>
&nbsp;<a href="https://skpkush.github.io/Sumitkprajapat/"><img src="https://img.shields.io/badge/Portfolio-live-58A6FF?style=flat-square&labelColor=0D1117&logo=github&logoColor=58A6FF"/></a>

</div>

<br/>

```sql
sumit_prajapat=# SELECT * FROM about WHERE honest = true;
```

I take data the whole way: **ingestion → Azure pipelines → SQL star schemas → Power BI dashboards → ML models** — and I lead every dashboard with **one quantified headline**, not a wall of charts.

**2+ years inside BFSI** selling and servicing insurance products *before* analyzing them — now a freelance Data Analyst with **Finonus Capital**. B.Com graduate, **Microsoft (PL-300 · AZ-900 · DP-900) and AWS certified**.

> `-- The kind of analyst who measures e-commerce retention on customer_unique_id — the real person —`
> `-- and flags a dataset cut-off artifact before anyone misreads it as a downturn.`
> `-- and says "the data can't prove this campaign worked" when a placebo test fails.`

**Domains** <kbd>Retail & FMCG</kbd> <kbd>Finance & Insurance</kbd> <kbd>Healthcare</kbd> <kbd>E-Commerce</kbd> &nbsp;·&nbsp; **Seeking** <kbd>Data Analyst</kbd> <kbd>BI Developer</kbd> <kbd>Power BI Developer</kbd>

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# EXPLAIN ANALYZE how_i_ship;
```

<div align="center">
<img src="assets/pipeline.svg" width="100%" alt="EXPLAIN ANALYZE how_i_ship: raw_data → azure_blob → data_factory → postgresql star schema → power_bi + ml → decisions, with quality gates: grain checks, null audits, dedup, reconcile to source, artifact-vs-signal test"/>
</div>

<img src="assets/divider.svg" width="100%"/>

```sql
sumit_prajapat=# SELECT project, headline_metric
sumit_prajapat-# FROM   featured_work
sumit_prajapat-# ORDER  BY impact DESC;
```

| `#`  | `project`                             | `headline_metric`                                  |
| :--- | :------------------------------------ | :------------------------------------------------- |
| `01` | Grocery Retail Analytics `NEW`        | 1.46M transactions → **50.6% of coupons go to habitual buyers** |
| `02` | Healthcare Insurance Claims Analytics | 558,211 claims → **226× fraud concentration**      |
| `03` | Mutual Fund Analytics Platform        | **9M+ NAV rows** · 10,571 funds · 51 AMCs          |
| `04` | Olist E-Commerce Analytics            | 112,650 records → **~97% one-time buyers** exposed |
| `05` | Customer Segmentation Engine          | RFM + 3 models · **Silhouette 0.52** · live app    |
| `06` | Queryscratch                          | **500 SQL questions** · in-browser SQL sandbox     |

`(6 rows)`

```sql
sumit_prajapat=# \x on   -- expanded display: full detail per project
```

<table>
  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://github.com/Skpkush/grocery-retail-analytics"><code>[01]</code> Grocery Retail Analytics</a> &nbsp;<sub><code>★ latest build</code></sub></h3>
      <p><b>1.46M real transactions · 2,469 households · does promo spend actually change behaviour?</b></p>
      <a href="https://github.com/Skpkush/grocery-retail-analytics"><img src="https://raw.githubusercontent.com/Skpkush/grocery-retail-analytics/main/docs/images/powerbi_1_executive_overview.png" width="100%" alt="Grocery Retail Analytics — Power BI Executive Overview"/></a>
      <table>
        <tr>
          <td align="center"><b>1.46M</b><br/><sub>transactions cleaned</sub></td>
          <td align="center"><b>50.6%</b><br/><sub>coupons → habitual buyers</sub></td>
          <td align="center"><b>225%</b><br/><sub>display + mailer lift</sub></td>
          <td align="center"><b>58 / 58</b><br/><sub>DAX reconciled to SQL</sub></td>
        </tr>
      </table>
      <p><sub>24-check data-quality gate → DuckDB star schema → 13 SQL analyses → difference-in-differences with placebo tests → 5-page Power BI report (44 DAX measures) + Streamlit app with a cite-or-refuse "ask the data" assistant. CI re-runs the full pipeline on every push.</sub></p>
      <p><code>-- impact: placebo tests failed → campaign ROI unmeasurable; recommended a 10% random holdout. SQL check caught 3 DAX bugs.</code></p>
      <p><kbd>Python</kbd> <kbd>DuckDB SQL</kbd> <kbd>statsmodels</kbd> <kbd>Power BI</kbd> <kbd>DAX</kbd> <kbd>Streamlit</kbd> <kbd>GitHub Actions</kbd></p>
      <p><a href="https://github.com/Skpkush/grocery-retail-analytics"><code>→ view repo</code></a> &nbsp; <a href="https://grocery-retail-analytics-gej2xcqxwhwypm7lvjhher.streamlit.app/"><code>🟢 live app</code></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics"><code>[02]</code> Healthcare Insurance Claims Analytics</a></h3>
      <p><b>558,211 Medicare claims → 226× fraud concentration finding</b></p>
      <p><sub>Azure Data Factory ingestion → PostgreSQL 9-table warehouse → scikit-learn fraud model (<b>90.1% recall · AUC 0.9573</b>) → 4-page executive Power BI report.</sub></p>
      <p><code>-- impact: $295.68M claim exposure flagged; 90.1% of fraud cases caught</code></p>
      <p><kbd>Azure ADF</kbd> <kbd>PostgreSQL</kbd> <kbd>scikit-learn</kbd> <kbd>Power BI</kbd></p>
      <p><a href="https://github.com/Skpkush/Healthcare-Insurance-Claims-Analytics"><code>→ view repo</code></a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/mf-analytics-platform"><code>[03]</code> Mutual Fund Analytics Platform</a></h3>
      <p><b>9M+ NAV rows · 10,571 funds · 51 AMCs</b></p>
      <p><sub>Production-grade 5-dimension / 4-fact star schema · full risk suite (Sharpe, Sortino, alpha/beta, drawdown) · Prophet 30/60/90-day NAV forecasts · Streamlit front-end.</sub></p>
      <p><code>-- impact: 10,571 funds across 51 AMCs made comparable on one risk framework</code></p>
      <p><kbd>Star Schema</kbd> <kbd>Python</kbd> <kbd>Prophet</kbd> <kbd>Streamlit</kbd></p>
      <p><a href="https://github.com/Skpkush/mf-analytics-platform"><code>→ view repo</code></a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard"><code>[04]</code> Olist E-Commerce Analytics</a></h3>
      <p><b>112,650-record warehouse · 40+ DAX measures</b></p>
      <p><sub>Uncovered <b>~97% one-time buyers</b> by measuring retention on the correct customer grain (<code>customer_unique_id</code>) · AI visuals · what-if price simulation.</sub></p>
      <p><code>-- impact: retention corrected from order grain to customer grain across 99,441 orders</code></p>
      <p><kbd>Power BI</kbd> <kbd>DAX</kbd> <kbd>SQL</kbd> <kbd>Power Query</kbd></p>
      <p><a href="https://github.com/Skpkush/Olist-E-Commerce-Analytics-Dashboard"><code>→ view repo</code></a></p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/Skpkush/Customer-Segmentation"><code>[05]</code> Customer Segmentation Engine</a></h3>
      <p><b>RFM + 3 clustering models · Silhouette 0.52</b></p>
      <p><sub>K-Means vs Hierarchical vs DBSCAN benchmarked head-to-head · CLV estimation · cohort analysis · deployed as an interactive app.</sub></p>
      <p><code>-- impact: 4 actionable customer segments with CLV, deployed live for stakeholders</code></p>
      <p><kbd>Python</kbd> <kbd>scikit-learn</kbd> <kbd>Pandas</kbd> <kbd>Streamlit</kbd></p>
      <p><a href="https://github.com/Skpkush/Customer-Segmentation"><code>→ view repo</code></a> &nbsp; <a href="https://customer-segmentation-g4vjra3jvttxstxguxhnff.streamlit.app/"><code>🟢 live demo</code></a></p>
    </td>
  </tr>

  <tr>
    <td colspan="2" valign="top">
      <h3><a href="https://www.queryscratch.com/"><code>[06]</code> Queryscratch — learn SQL by doing</a></h3>
      <p><b>500 SQL practice questions · in-browser sandbox · free for students</b></p>
      <p><sub>Real queries run client-side via <b>sql.js / WebAssembly</b> — no install, no server round-trip. Streak tracking and per-user progress on Supabase auth.</sub></p>
      <p><kbd>SQL</kbd> <kbd>sql.js</kbd> <kbd>WebAssembly</kbd> <kbd>Supabase</kbd> <kbd>JavaScript</kbd></p>
      <p><a href="https://github.com/Skpkush/Queryscratch"><code>→ view repo</code></a> &nbsp; <a href="https://www.queryscratch.com/"><code>🟢 live site</code></a></p>
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
| `data_engineering` | <kbd>SQL</kbd> <kbd>PostgreSQL</kbd> <kbd>DuckDB</kbd> <kbd>Azure Data Factory</kbd> <kbd>Star Schema</kbd> <kbd>ETL</kbd>      |
| `python_ml`        | <kbd>Python</kbd> <kbd>Pandas</kbd> <kbd>NumPy</kbd> <kbd>scikit-learn</kbd> <kbd>statsmodels</kbd> <kbd>Prophet</kbd> <kbd>Streamlit</kbd> |
| `cloud_and_ops`    | <kbd>Microsoft Azure</kbd> <kbd>AWS</kbd> <kbd>Git</kbd> <kbd>GitHub Actions</kbd> <kbd>Jupyter</kbd>                                   |

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
