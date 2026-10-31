# YottaFlex Supply Chain Recall System

## Overview
A deterministic synthetic supply-chain traceability and recall project.

The project generates suppliers, material lots, products, bills of materials,
production orders, finished lots, shipments, customers and deliveries.

It includes anomaly scenarios and a basic genealogy engine to trace affected
raw material lots to production orders, finished lots and downstream customers.

## Technology
- Python
- Pandas
- NumPy
- SQLite-compatible data design
- CSV and JSON

## Reproducibility
Random seed: 20261022

## Run
Open the Google Colab notebook and execute the cells in order.

## Generated outputs
- Master data
- Production consumption records
- Finished lots
- Shipment and delivery records
- Anomaly records
- Ground-truth labels
- Genealogy results
- Recall scope summary

## Limitations
This is a synthetic demonstration. The genealogy output identifies downstream
customers and deliveries. Full production-grade notification, quarantine,
recovery, authentication and live ERP integrations are not implemented.

All records are synthetic and do not represent real companies or customers.
