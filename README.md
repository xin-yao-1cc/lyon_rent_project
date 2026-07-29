# Lyon Rental Market Analytics

## Project Overview

This project builds an end-to-end Data Engineering pipeline using Databricks to analyze the rental market in Lyon.

The objective is to transform public datasets into business insights for:

- tenants looking for affordable areas
- investors looking for attractive rental opportunities

The project follows the Medallion Architecture (Bronze → Silver → Gold) using Delta Lake.

---

## Business Questions

### Rental Market

- Which districts have the highest regulated rent?
- How does rent vary by district?
- How does rent vary by apartment size?
- How does furnishing impact rent?
- How does building age affect rent?

### Investment Analysis

- Which districts provide the best balance between purchase price and rental income?
- Which districts generate the highest gross rental yield?
- Which districts have the highest rent per square meter?
- Where is rental regulation the most restrictive?

---

## Data Sources

| Dataset | Source |
|---------|---------|
| Rent Regulation | [data.gouv.fr](https://www.data.gouv.fr/datasets/encadrement-des-loyers-de-la-metropole-de-lyon-2023-2024) |
| Property Prices (DVF) | [data.gouv.fr](https://www.data.gouv.fr/datasets/dvf-open-data) |


---

## Architecture

Bronze
↓

Raw CSV

↓

Silver

Clean & Standardized Data

↓

Gold

Business KPIs

↓

Dashboard

---

## Technologies

- Databricks
- PySpark
- Delta Lake
- SQL
- Git
- Power BI / Databricks Dashboard

---

## KPIs

Average regulated rent

Median rent

Rent by district

Rent by apartment type

Rent by building age

Gross rental yield

Price-to-rent ratio

Investment score

---

## Dashboard

(Add screenshots)

---

## Future Improvements

- Machine Learning prediction
- Time series analysis
- Real rental advertisements
- Population statistics
- School accessibility
