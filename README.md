# Ounass - Senior Data Scientist Case Study

## Setup

Python 3.11.9, managed with [uv](https://github.com/astral-sh/uv).

```bash
uv sync
source .venv/bin/activate
```

## Repository Structure

```
dev/          # Ad hoc exploration and experimentation notebooks (scratch space)
final/        # Deliverables: structured notebooks and documents
  search/     # Search case study
  forecasting/  # Forecasting case study
data/
  raw_data/   # Source datasets (parquet)
```

## Deliverables

All final work lives under `final/`. Each subdirectory contains Jupyter notebooks and, where appropriate, PDFs (documents, presentations).

**Search**

| File | Description |
|------|-------------|
| `Part 1 - Data Understanding & Diagnostics.ipynb` | EDA and data quality |
| `Part 2 - Modeling Task (Core).ipynb` | Model development |
| `Part 3 - Search System Design.pdf` | System design document |
| `Part 4 - Evaluation & Experimentation.pdf` | Evaluation framework |
| `Ounass_Search_CaseStudy.pdf` | Presentation |

**Forecasting**

| File | Description |
|------|-------------|
| `Part 1 - Data Understanding.ipynb` | EDA and data quality |
| `Part 2 & 3 - Forecasting and Evaluation.ipynb` | Model development and evaluation |
| PDFs | Exported versions of the above notebooks |
