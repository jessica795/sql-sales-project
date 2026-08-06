# sql-sales-project

\# SQL Sales Analysis



Practicing real-world SQL by querying a sales transactions dataset directly, 

using SQLite. Same dataset as my \[pandas-based analysis](https://github.com/jessica795/sales-data-analysis), 

this time answering business questions with pure SQL.



\## Dataset



\- Source: \[Sample Sales Data](https://www.kaggle.com/datasets/kyanyoga/sample-sales-data) (Kaggle)

\- 2,823 transactions loaded into a SQLite database for querying



\## Tools Used



\- SQL (SQLite)

\- Python (pandas, sqlite3) — used to load data and execute queries in Google Colab



\## SQL Concepts Practiced



| Concept | Query |

|---|---|

| Aggregation (`SUM`, `COUNT`) | Total orders and total revenue |

| `GROUP BY` + `ORDER BY` | Revenue by product line, ranked highest to lowest |

| `GROUP BY` + `LIMIT` | Top 5 customers by total spend |

| Subquery | Orders with sales above the overall average |

| `CASE` statement | Bucketing orders into Low/Medium/High sales tiers |

| `HAVING` | Countries with more than 100 orders |

| Window function (`SUM() OVER`) | Running total of revenue by year |



\## Key Findings



\- \*\*Total revenue\*\*: $10,032,628.85 across 2,823 orders

\- \*\*Classic Cars\*\* is the top-performing product line at $3.9M

\- \*\*Euro Shopping Channel\*\* is the top customer, spending $912,294

\- Revenue grew from \*\*$3.5M (2003)\*\* to \*\*$4.7M (2004)\*\*, with a cumulative 

&#x20; running total of \*\*$10M by end of 2005\*\* (partial year)

\- Most orders (1,709 of 2,823) fall into the \*\*Medium\*\* sales tier ($2,000–$5,000)



\## Files



\- `sql\_analysis.ipynb` — full notebook with all SQL queries and results

\- `sales\_data\_sample.csv` — raw dataset



\## What I Learned



Applied core and intermediate SQL — filtering, aggregation, subqueries, 

conditional logic, and window functions — to answer real business questions, 

building on the same dataset explored earlier with pandas to compare both approaches.

