# Global Quality of Life Interactive Dashboard

![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)
![Streamlit](https://img.shields.io/badge/Streamlit-1.25%2B-red.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0%2B-yellow.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.15%2B-green.svg)

**🔴 Live Demo:** [**https://quality-of-life-dashboard.streamlit.app/**](https://quality-of-life-dashboard.streamlit.app/)

---

## Overview

This project is an interactive, multi-page dashboard designed to explore, compare, and analyze global quality-of-life indicators. Quality of life is shaped by numerous factors, but the data is often fragmented, making it difficult to analyze trends or compare regions. This tool addresses that gap by consolidating key metrics into a single, visually engaging platform to support data-driven decision-making.

The dashboard is built for a diverse audience, including:
* **Policymakers** evaluating national performance.
* **Researchers** analyzing socio-economic and environmental trends.
* **Individuals & Expats** making informed relocation or investment decisions.

![Dashboard Screenshot](<https://github.com/SinanSamah/quality-of-life-dashboard/blob/main/dashboard-preview.png>)

---

## Key Features

The application is composed of several analytical modules:

* **🗺️ World Map Explorer:** An interactive choropleth map to visualize global variations in key indicators. Features dynamic filters for continents, a log-scale option for skewed data, and detailed hover-over tooltips.
* **📊 Country & Continent Comparison:** A side-by-side comparison tool that uses radar, bubble, and bar charts to analyze the strengths and weaknesses of any two selected entities across multiple metrics.
* **📈 Top vs. Bottom Analysis:** A module to instantly identify and compare the highest and lowest-performing countries for any selected indicator, complete with auto-generated textual insights that explain real-world implications.
* **🌍 Global Metrics View:** Presents aggregate statistics and hierarchical data visualizations (like sunburst charts) to understand indicator distributions at both continental and country levels.

---

## Technical Stack

* **Language:** Python
* **Dashboard Framework:** Streamlit
* **Data Manipulation:** Pandas
* **Visualization Libraries:** Plotly, Altair
* **Data:** The primary dataset is from Numbeo's Quality of Life Index, combined with a country-continent classification dataset.

---

## Setup and Local Installation

To run this project on your local machine, please follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/SinanSamah/quality-of-life-dashboard.git
    cd quality-of-life-dashboard
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    # For Windows
    python -m venv venv
    .\venv\Scripts\activate

    # For macOS/Linux
    python3 -m venv venv
    source venv/bin/activate
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Run the Streamlit application:**
    ```bash
    streamlit run main.py
    ```
    The application should now be open and running in your web browser.

---
## Data Source
The data used in this dashboard is sourced from [Numbeo's Quality of Life Indices](https://www.numbeo.com/quality-of-life/), a crowd-sourced global database of reported consumer prices, perceived crime rates, and quality of life indicators.
