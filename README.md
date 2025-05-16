# Stock and Revenue Data Analysis: Tesla & GameStop

This repository contains code and data for extracting, processing, and visualizing stock price and revenue data for Tesla (TSLA) and GameStop (GME).

## Project Overview

- Extract stock price data using Yahoo Finance API (`yfinance` library).
- Web scrape quarterly revenue data from provided IBM Skills Network URLs using `requests` and `BeautifulSoup`.
- Clean and structure the data into Pandas DataFrames.
- Plot stock prices and revenue data for Tesla and GameStop using Matplotlib.
- Data covers the maximum available period but plots are limited to June 2021.

## Directory Structure

- `data/` : Contains raw or saved CSV files for stock and revenue data.
- `notebooks/` : Jupyter notebooks for data extraction, cleaning, and visualization.
- `scripts/` : Python scripts for automation of data extraction and plotting.
- `requirements.txt` : List of required Python packages.

## Getting Started

### Prerequisites

- Python 3.x
- Install dependencies with:
