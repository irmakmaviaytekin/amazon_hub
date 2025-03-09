# amazon_hub

# Warehouse Location Optimization

## Project Overview
The goal of this project is to help e-commerce brand cut losses off of returned products and includie returned products back in flow. It leverages a data-driven approach to determine the optimal locations for new warehouses in the City of Toronto. Using synthetic data generated from archival sources and processed through Generative AI, this project helps businesses strategically select warehouse sites to maximize efficiency and profitability.

## Objective
Identify optimal warehouse locations in Toronto by analyzing key demographic and economic parameters.

## Data Source
- Synthetic data based on City of Toronto archives.
- Data was processed using Generative AI and compiled into an Excel spreadsheet.

## Methodology
- Data processing and code development were executed using Gemini, Google AI Studio, and Google Colab.
- Weighted parameters were used to rank potential locations.

## Key Parameters for Location Selection
- **Population (Ages 15-64):** Target areas with active consumer bases.
- **Transportation Services:** Accessibility to warehouses is essential.
- **Median Total Income:** Preference for wealthier neighborhoods with high purchasing power.
- **Purchase and Return Density:** Priority given to locations with significant shopping activity.
- **Land Availability and Cost:** Optimize warehouse placement by considering affordable and accessible land.

## Parameter Weights
Parameters were ranked according to their influence on the optimal location decision:
- Purchase Density: 50%
- Land Availability & Cost: 40%
- Transportation Services: 20%
- Median Total Income: 15%
- Population (15-64): 10%

## Workflow
1. **Read Input Data**: Extract synthetic data from provided Excel files.
2. **Process Data with Parameter Weights**: Apply parameter weights to evaluate potential locations.
3. **Rank Warehouse Location Options**: Generate and print a ranked list of optimal warehouse locations.

## Resources
- [Dataset Spreadsheet](https://docs.google.com/spreadsheets/d/1jbCxKx4ZUn23SUIZYlU63XSrBqbanL8D5pbKgrQZuME/edit?usp=sharing)

## Tools Used
- Gemini AI
- Google AI Studio
- Google Colab

## Application
This model and workflow are suitable for businesses and analysts involved in logistics planning, supply chain management, and strategic business development.

