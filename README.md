# MSDS670 Final Project: Marvel by the Numbers

This project visualizes Marvel Cinematic Universe box office performance using Python, Pandas, and Matplotlib.

## Research Question

How has Marvel Cinematic Universe movie performance changed over time based on worldwide box office revenue, production budget, and release-era performance?

## Visualizations

1. Annual worldwide MCU box office revenue by release year
2. Top 10 MCU movies by worldwide box office revenue
3. Production budget vs. worldwide box office revenue
4. Average worldwide box office revenue by MCU release era

## How to Run

```bash
pip install -r requirements.txt
python src/create_visualizations.py
```

The charts will export to the `images/` folder as PNG files.

## Data Notes

The dataset is a manually curated CSV from The Numbers' Marvel Cinematic Universe franchise table. Dollar values are unadjusted nominal box office amounts and are not adjusted for inflation.
