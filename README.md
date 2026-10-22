# Applied Data Analysis with Python

Case studies and practical notebooks in data cleaning, exploratory analysis, visualization, statistics, and predictive modelling. Developed during Data Science training at Entri.

## Start here

| Case study | Main question | Skills |
|---|---|---|
| [Employee workforce analysis](employee-workforce-analysis.ipynb) | How do team composition and salary expenditure vary? | Pandas, aggregation, percentages, visualization |
| [Customer retention statistics](customer-retention-statistics.ipynb) | Which customer characteristics relate to retention or churn? | Descriptive statistics, statistical tests, interpretation |
| [California housing regression](California_Housing_Regression/README.md) | How do regression models compare when predicting median house values? | Pipelines, validation, tuning, regression metrics |
| [Titanic visualization](titanic-exploratory-visualization.ipynb) | What do passenger distributions and relationships look like? | Matplotlib, Seaborn, chart interpretation |

The employee and customer notebooks require course datasets that are not included. Existing notebook outputs can be reviewed, but a complete rerun needs those inputs. See [dataset requirements](data/README.md).

## Additional notebooks

| Notebook | Focus |
|---|---|
| [Data cleaning and preprocessing](data-cleaning-and-preprocessing.ipynb) | Missing values, duplicates, encoding, scaling |
| [Classification model comparison](classification-model-comparison.ipynb) | Educational comparison using scikit-learn's breast cancer dataset |
| [Regression model comparison](regression-model-comparison.ipynb) | Introductory model comparison; the fuller housing case study is linked above |
| [Wine quality mathematics](wine-quality-mathematics.ipynb) | Linear algebra and probability exercises |
| [NumPy and Pandas practice](numpy-pandas-practice.ipynb) | Arrays and DataFrames |
| [Python data structures](python-data-structures.ipynb) | Collections and basic operations |
| [Banking console practice](banking-console-practice.ipynb) | Interactive Python programming exercise |

## Employee-analysis notes

The course workbook uses basketball-team and position labels. It is an educational dataset, not evidence of work for an employer. The earlier run reported a weak positive age/salary correlation of approximately 0.16 for the retained sample. Correlation does not establish causation, and dropping missing rows may change the sample composition.

The team-percentage calculation now uses count / total × 100 across all teams. Age-group boundaries include younger records, and salary-chart axis labels have been corrected. Heights are explicitly marked as simulated. Outputs affected by these edits are cleared until the original workbook can be supplied and rerun.

## Run locally

Use Python 3.10 or newer. Open a terminal in this repository:

```bash
python -m venv .venv
# Windows: .venv\Scripts\activate
# macOS/Linux: source .venv/bin/activate
python -m pip install -r requirements.txt
python -m jupyter notebook
```

Open a notebook and run its cells in order. Use the notebook's folder as the working directory. Built-in datasets may need internet access on first download; some exercises request interactive input or write CSV/PNG files. Package versions are not pinned, so older exercises may need compatibility adjustments.

## More projects

- [Car price analysis and prediction](https://github.com/Mohamedrashid117/car-price-prediction)
- [Hotel booking cancellation analysis](https://github.com/Mohamedrashid117/hotel-booking-cancellation)

## Maintaining this portfolio

[Step-by-step GitHub guide](docs/PORTFOLIO_GUIDE.md) · [Ready-to-copy profile README](docs/profile-README.md)
