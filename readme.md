-- Gene Expression and Anthropometric Data Analysis

---- Overview
This repository contains the solution for Gene Expression, which involves merging and analyzing gene expression and anthropometric data from multiple labs. The goal is to combine inconsistent datasets, study BMI distribution across populations, and explore BMI's relationship with gene expression.


---- Requirements
- Python 3.x
- Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `jupyter`
- Install via: `pip install pandas numpy matplotlib seaborn jupyter`

---- Running the Code
1. Clone this repository: `git clone https://github.com/7skaliahmed07/Gene-Expression-Data-Analysis`
2. Place the raw data files (`NL.csv`, `PL.csv`, `UK.csv`, `US.csv`, `genes.csv`) in the `data/` directory.
3. Open the notebook: `cd analysis && jupyter notebook analysis.ipynb`
4. Run all cells to execute the analysis.

---- Steps
1. **Setup**: Environment preparation.
2. **Load Data**: Read raw CSV files.
3. **Inconsistencies**: Identify data issues.
4. **Standardize**: Rename columns consistently.
5. **Convert Units**: Adjust UK units, calculate BMI.
6. **Handle Missing**: Fill/drop missing values, standardize `smokes`.
7. **Merge**: Combine datasets into `combined_dataset.csv`.
8. **BMI Distribution**: Boxplot and stats by population.
9. **BMI vs Genes**: Correlation and scatterplot.
10. **Finalize**: Document in markdown.

---- Outputs
- `out/combined_dataset.csv`: Merged dataset.
- Plots: BMI distribution, BMI vs GeneA scatterplot.
- Console: Summary statistics and correlations.

