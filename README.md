# Unstructured Data Analysis: Car Comments Project

This project performs comprehensive unstructured data analysis on car forum comments, including web scraping, text processing, statistical analysis, and business intelligence extraction using NLP techniques.

## Project Overview

**Objective:** Analyze ~8-10k car comments from online forums to identify brand associations, customer sentiment patterns, and business insights.

**Key Methods:** Zipf's Law analysis, lift calculations, multidimensional scaling (MDS), and text frequency analysis.

**Data:** `car_comments_zm.csv` (~5MB, 8-10k comments with userid, date, message)

---

## Repository Structure

```
Unstructured-Data-1/
├── README.md                           # This file
├── data/
│   ├── car_comments_zm.csv            # Scraped forum comments (8-10k posts)
│   └── car_brands_lift.xlsx           # Toy data validation set
├── notebooks/
│   ├── scraper_zm.ipynb               # Web scraper for forum data
│   ├── zipf_zm.ipynb                  # Zipf's Law analysis (Task A)
│   ├── vectorizer_lift_MDS_zm.ipynb   # Text analysis, lift, MDS (Tasks B-H)
│   ├── Task_BCDE.ipynb                # Task-specific notebook
│   └── Assignment_1.ipynb             # Final integrated analysis
└── .git/                              # Version control
```

---

## Notebooks & Tasks

| Task | Description | Notebook | Status |
|------|-------------|----------|--------|
| **Scraper** | Python scraper for forum HTML; handles threading, removes block quotes | `scraper_zm.ipynb` | ✓ Complete |
| **Task A: Zipf Test** | OLS regression on log-log distribution; slope test; top-100 words analysis | `zipf_zm.ipynb` | ✓ Complete |
| **Task B: Top-10 Brands** | Brand frequency analysis with stopword removal | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task C: Lift (Top-10)** | Co-occurrence lift table for top-10 brands | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task D: MDS (Top-10)** | 2D MDS visualization of brand distances (1/lift) | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task E: Insights (C & D)** | Business insights from lift and MDS analysis | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task F: Top-5 Attributes** | Frequency table of car attributes and brand associations | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task G: Insights (F)** | Client recommendations from attribute-brand relationships | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |
| **Task H: Aspirational Brand** | Identify most aspirational brand and business implications | `vectorizer_lift_MDS_zm.ipynb` | ✓ Complete |

---

## Quick Start

### Running Notebooks Locally

1. **Install dependencies:**
   ```bash
   pip install pandas numpy scipy scikit-learn matplotlib seaborn jupyter
   ```

2. **Run a notebook:**
   ```bash
   jupyter notebook notebooks/zipf_zm.ipynb
   ```

### Running in Google Colab

Click the Colab badges below to run notebooks directly:

| Notebook | Colab |
|----------|-------|
| `Assignment_1.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/notebooks/Assignment_1.ipynb) |
| `scraper_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/notebooks/scraper_zm.ipynb) |
| `vectorizer_lift_MDS_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/notebooks/vectorizer_lift_MDS_zm.ipynb) |
| `zipf_zm.ipynb` | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/AHMerrill/Unstructured-Data-1/blob/main/notebooks/zipf_zm.ipynb) |

**Note:** In Google Colab, use "Save to GitHub" at the top to commit notebook changes. Download any newly created CSV/data files and re-commit manually.

---

## Data Files

- **`data/car_comments_zm.csv`** (5.1 MB): Main dataset with columns: `userid`, `date`, `message`
- **`data/car_brands_lift.xlsx`**: Validation data for lift calculations

---

## Key Findings & Insights

The analysis reveals:
- **Brand Associations:** Top 10 brands show strong co-occurrence patterns
- **Customer Sentiment:** Lift analysis identifies brand preferences and competitive relationships
- **Market Positioning:** MDS visualization maps brand proximity based on customer perception
- **Attribute-Brand Links:** Specific car attributes cluster with particular brands

---

## Contributors

- **Zan Merrill** (AHMerrill): Scraping, analysis, Zipf test
- **Maru**: Lift validation, plot enhancements
- **Kristen**: Insights (Tasks E & H)
- **Ethan**: Attribute frequency analysis
- **Nikhil**: Aspirational brand analysis
- **Grace**: Final integration (Assignment_1.ipynb)

---

## Technologies

- **Python 3.x**
- **Pandas**: Data manipulation
- **NumPy**: Numerical computing
- **Scikit-learn**: Feature extraction & text vectorization
- **SciPy**: Sparse matrices & MDS
- **Matplotlib/Seaborn**: Visualization
- **Jupyter Notebooks**: Interactive analysis

---

## How to Contribute

1. Clone the repository
2. Create a new branch for your changes
3. Make edits to notebooks or data files
4. Commit with clear messages
5. Push to main and use "Save to GitHub" in Colab if applicable

---

*Last Updated: February 2026*
*Course: Unstructured Data 1 | UT Austin MSBA Program*
