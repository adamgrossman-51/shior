# Shior — Streamlit Dashboard

A simple **Streamlit** dashboard demo that shows KPI cards, an interactive time-series chart, and a data table using **pandas** + **Plotly**.

## Features

- **Sidebar filter** to switch between metrics (Sales / Revenue / Users / Engagement)
- **KPI cards** (totals + average engagement)
- **Interactive line chart** (Plotly)
- **Data table** preview

## Tech Stack

- **Python**
- **Streamlit**
- **pandas**
- **plotly**

## Project Structure

```text
.
├─ dashbord.py
└─ test.py
```

## Getting Started

### 1) Prerequisites

- Python 3.9+ recommended

### 2) Install dependencies

```bash
python -m pip install --upgrade pip
pip install streamlit pandas plotly
```

### 3) Run the app

```bash
streamlit run dashbord.py
```

Then open the local URL shown in the terminal (usually `http://localhost:8501`).

## Notes

- The dashboard currently uses **sample in-code data** (no external files required).
- File name is `dashbord.py` (spelled without the second “a”).

## Contributing

PRs are welcome. If you want to extend it, good next steps:

- Load data from a CSV/DB/API
- Add date ranges and more filters
- Add multiple charts and export options

## License

MIT (or your choice). If you want, tell me which license you prefer and I’ll add a `LICENSE` file.

