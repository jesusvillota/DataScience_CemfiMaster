
# Data Science for Economics (Practicals)

## Schedule and location

- **Session #1**: Thursday, October 2, 9:30 AM - 11:00 AM @ Room M1 (CEMFI)
- **Session #2**: Tuesday, October 27, 15:00 AM - 16:30 AM @ Room M1 (CEMFI)

Please bring your laptop to class with `VSCode` and `uv` installed and ready to run Python code.

## Repository structure

```bash
.
├── data/                          # Data files for exercises and examples
│   ├── death-rate-who.csv
│   ├── gdp-per-capita-worldbank.csv
│   └── population-unwpp.csv
├── Session1/                      # Session 1 notebooks
│   ├── 1_1.ipynb                 # Introduction to Python (Part I)
│   └── 1_2.ipynb                 # Introduction to Python (Part II)
├── Session2/                      # Session 2 materials
│   ├── 2_1_Scraping_Intro.ipynb  # Web scraping introduction
│   ├── 2_2_BIS_Scraper_I.ipynb   # BIS scraper (Part I)
│   ├── 2_2_BIS_Scraper_II.ipynb  # BIS scraper (Part II)
│   └── Extra_BCU_Scraper.ipynb   # BCU scraper (extra)
├── Installation_Guide_VSCode_uv.pdf  # Installation guide
├── main.py                        # Main Python script
├── pyproject.toml                # Project dependencies (uv)
└── uv.lock                       # Locked dependencies for reproducibility
```

## Session plan

### Session 1: Introduction to Python

#### **1_1.ipynb - Introduction to Python | Part I**

- Overview of Python and setup with UV package manager
- Jupyter Notebooks fundamentals
- Python syntax basics:
  - Variables and naming conventions
  - Primitive data types (int, float, string, bool, None)
  - Container data types (tuples, lists, dictionaries)
  - Functions and control flow (if/elif/else, for/while loops)
- Introduction to NumPy:
  - Creating and managing arrays
  - Array operations (element-wise and matrix multiplication)
  - Indexing and slicing

#### **1_2.ipynb - Introduction to Python | Part II**

- Introduction to Pandas:
  - Series: creation, operations, and slicing
  - DataFrames: creation, indexing, and operations
  - Data manipulation (adding/removing columns, sorting, merging)
  - Applying functions
- Data visualization:
  - Matplotlib basics
  - Seaborn for statistical graphics
  - Creating plots (scatter, line, bar, histograms, heatmaps)

## Prerequisites

- Python 3.11+
- VSCode
- UV package manager installed with Python

## Getting started

1. Clone this repository
2. Navigate to the project directory
3. Install dependencies: `uv sync`
4. Open notebooks in VSCode and select the UV environment

## Contact

- Email: <jesus.villota@cemfi.edu.es>
- LinkedIn: <https://www.linkedin.com/in/jesusvillotamiranda/>
