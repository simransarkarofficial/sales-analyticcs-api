# Sales Analytics API (SQL + FastAPI)

## Overview
This project is a backend analytics system built using FastAPI and SQL (SQLite) on a real-world sales dataset.

## Features
- Total Revenue Calculation
- Top Selling Products
- Revenue by Region
- REST API Endpoints

## Tech Stack
- Python
- FastAPI
- SQLite (SQL)
- Pandas

## API Endpoints
- /total_revenue
- /top_products
- /revenue_by_region

## How to Run
```bash
pip install -r requirements.txt
uvicorn app.main:app --reload
