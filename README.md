# Kyiv Air Raid Analysis

A data analysis pet project built as part of the **Agentic AI School** program. The notebook explores patterns in air raid alert data for Kyiv, Ukraine, using Python-based exploratory data analysis and visualization.

## Overview

This project analyzes historical air raid alert events in Kyiv — examining how long alerts last, when they tend to occur, and how they relate to weapon types. The goal is to surface meaningful temporal and statistical patterns from the data.

## Contents

| File | Description |
|---|---|
| `kyiv_air_raid_analysis.ipynb` | Main Jupyter notebook with all analysis and visualizations |
| `fig1_duration_distribution.png` | Distribution of alert durations |
| `fig2_starttime_rose.png` | Polar/rose chart of alert start times by hour |
| `fig3_duration_by_time.png` | Alert duration broken down by time of day |
| `fig4_duration_vs_weapons.png` | Relationship between alert duration and weapon types |
| `fig5_hour_month_heatmap.png` | Heatmap of alert frequency by hour and month |

## Key Analyses

- **Duration distribution** — how long air raid alerts typically last
- **Temporal patterns** — which hours and months see the most alerts
- **Weapon type correlation** — whether certain weapon types are associated with longer alerts
- **Time-of-day breakdown** — alert behavior across different parts of the day

## Tech Stack

- Python (Jupyter Notebook)
- pandas, matplotlib / seaborn (data processing and visualization)

## Getting Started

```bash
git clone https://github.com/rudakovskyi/Agentic_AI_School_pet_project.git
cd Agentic_AI_School_pet_project
jupyter notebook kyiv_air_raid_analysis.ipynb
```

## Context

This project was created as a hands-on learning exercise during the Agentic AI School program, applying data analysis skills to real-world open data about air raid alerts in Ukraine.
