
# Data Science for Economics (Practicals)

## Schedule and location

- **Session #1**: Thursday, October 2, 9:30 AM - 11:00 AM @ Room M1 (CEMFI)
- **Session #2**: Tuesday, October 27, 15:00 PM - 16:30 PM @ Room M1 (CEMFI)
- **Session #3**: Thursday, November 19, 9:30 AM - 11:00 AM @ Room M1 (CEMFI)

Please bring your laptop to class with `VSCode` and `uv` installed and ready to run Python code.

## Repository structure

```bash
.
├── data/                          # Data files for exercises and examples
│   ├── all_ECB_speeches.csv
│   ├── death-rate-who.csv
│   ├── gdp-per-capita-worldbank.csv
│   └── population-unwpp.csv
├── Session1/                      # Session 1 notebooks
│   ├── 1_1.ipynb                 # Introduction to Python (Part I)
│   └── 1_2.ipynb                 # Introduction to Python (Part II)
├── Session2/                      # Session 2 materials
│   ├── 2_1_Scraping_Intro.ipynb  # Web scraping introduction
│   ├── 2_2_BIS_Scraper_I.ipynb   # BIS scraper (Part I)
│   ├── 2_3_BIS_Scraper_II.ipynb  # BIS scraper (Part II)
│   ├── 2_4_Forecasting_Professions.ipynb  # Forecasting professions exercise
│   ├── Extra_BCU_Scraper.ipynb   # BCU scraper (extra)
├── Session3/                      # Session 3 materials
│   ├── 3_1_LLM_Intro.ipynb       # Introduction to Large Language Models
│   ├── 3_2_LLM_Fine_Tuning.ipynb  # Fine-tuning LLMs
│   ├── 3_3_LLM_Function_Calling.ipynb  # LLM function calling
├── Installation_Guide_VSCode_uv.pdf  # Installation guide
├── main.py                        # Main Python script
├── pyproject.toml                # Project dependencies (uv)
├── uv.lock                       # Locked dependencies for reproducibility
└── README.md                     # This file
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

### Session 2: Web Scraping

#### **2_1_Scraping_Intro.ipynb - Scrape it like you mean it!**

- Introduction to web scraping:
  - Definition and use cases
  - Ethical considerations and legal aspects
  - HTTP status codes and requests
- Tools and libraries:
  - Using `requests` for HTTP requests
  - Parsing HTML with `BeautifulSoup`
  - Basic scraping patterns

#### **2_2_BIS_Scraper_I.ipynb - Scraping Central Bank Speeches from the BIS (Part I)**

- Understanding website structure and dynamic content
- Handling pagination in web scraping
- Building a scraper for BIS central bank speeches:
  - Extracting speech metadata
  - Downloading PDF documents
  - Organizing scraped data

#### **2_3_BIS_Scraper_II.ipynb - Scraping Central Bank Speeches from the BIS (Part II)**

- Advanced scraping techniques:
  - Using Selenium for dynamic web pages
  - PDF text extraction with PyPDF2
  - Handling file downloads and organization
- Setting up project structure:
  - Directory management
  - Data organization and storage

#### **2_4_Forecasting_Professions.ipynb - Who is the Econometrician in the room?**

- Combining web scraping with machine learning:
  - Image retrieval and processing
  - Profession classification using ML models
  - Forecasting applications

#### **Extra_BCU_Scraper.ipynb - BCU Scraper (Extra)**

- Additional practice with web scraping
- Scraping from Banco Central del Uruguay (BCU) website

### Session 3: Large Language Models (LLMs)

#### **3_1_LLM_Intro.ipynb - Introduction to Large Language Models**

- Fundamentals of LLMs:
  - What are Large Language Models?
  - Transformer architecture overview
  - Pre-trained models and their applications
- Working with LLMs:
  - Using the `transformers` library
  - Text generation and completion
  - Model visualization with `bertviz`

#### **3_2_LLM_Finetuning.ipynb - Fine-Tuning Large Language Models**

- Fine-tuning techniques:
  - Parameter-Efficient Fine-Tuning (PEFT)
  - LoRA (Low-Rank Adaptation) method
  - Training custom models on domain-specific data
- Practical implementation:
  - Preparing datasets for fine-tuning
  - Training configuration and hyperparameters
  - Model evaluation and checkpointing
- Applications:
  - Text classification tasks
  - Domain adaptation for economic/financial texts

#### **3_3_LLM_II_Function_Calling.ipynb - Structured Data with LLMs Done Right**

- Function calling and structured output:
  - Defining tool schemas for LLM function calls
  - Implementing function calling patterns
  - Validating and executing LLM-requested functions
- Practical applications:
  - News → firm-level shocks: extracting affected firms and classifying shock types
  - Central bank speeches → policy stance classification and economic indicator extraction
  - Structured data extraction from unstructured text

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
