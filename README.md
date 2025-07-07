# Dynamic Pricing for Urban Parking Lots 🚗📈

## Overview

This project simulates a real-time dynamic pricing system for 14 urban parking lots using vehicle demand, traffic data, and event conditions. It's part of the Summer Analytics 2025 Capstone by the Consulting & Analytics Club × Pathway.

---

##  Tech Stack

- Python (NumPy, Pandas)
- Pathway (for real-time streaming)
- Bokeh (for visualizations)
- Google Colab
- GitHub

---

##  Project Architecture

```mermaid
graph TD
    A[Data Ingestion (CSV)] --> B[Pathway Real-time Table]
    B --> C[Pricing Logic Engine]
    C --> D[Model 1 - Baseline]
    C --> E[Model 2 - Demand-Based]
    C --> F[Model 3 - Competitive Pricing]
    F --> G[Output Pricing Table]
    G --> H[CSV Export / Bokeh Visualization]
