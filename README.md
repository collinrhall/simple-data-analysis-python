# simple-data-analysis-python
Beginner Python project using lists, loops, and arithmetic to derive business insights from salon pricing and sales data.
# Carly's Clippers - Business Metrics Analysis

A Python data analysis project exploring sales and pricing data for a fictional hair salon.

## Project Overview

This project analyzes two weeks of business data for Carly's Clippers to calculate key metrics that help inform operational decisions. Working with parallel lists of hairstyle names, prices, and weekly purchase counts, the project demonstrates core Python skills including list operations, loops, and basic statistics.

## Dataset

The project uses three parallel lists where each index represents the same hairstyle:

| List | Description |
|------|-------------|
| `hairstyles` | Names of cuts offered at the salon |
| `prices` | Price of each hairstyle (in dollars) |
| `last_week` | Number of times each style was purchased last week |

**Example:** Index 0 represents the `"bouffant"` hairstyle, priced at `$30`, purchased `2` times last week.

## Skills Demonstrated

- Python list indexing and iteration
- Arithmetic operations and running totals
- Calculating averages and summary statistics
- List comprehensions
- Drawing business conclusions from raw data

## How to Run

1. Clone the repo
2. Make sure Python 3 is installed
3. Run the script:

```bash
python script.py
```

No external libraries required -- this project uses only built-in Python.

## Key Metrics Calculated

- Average price of all hairstyles
- Hairstyles priced below the average (for a potential discount promotion)
- Total revenue generated last week
- Average daily revenue

## Context

This is a guided project completed on [Codecademy](https://www.codecademy.com/) as part of learning Python fundamentals. The business scenario and data are fictional.
