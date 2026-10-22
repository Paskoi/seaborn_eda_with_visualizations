# seaborn_eda_with_visualizations

Learning: exploratory data analysis of seaborn datasets with visualizations, cleaning and written conclusions.

Each dataset gets its own notebook.

## Datasets

| Dataset | Notebook | Status |
|---|---|---|
| tips | [datasets/tips/tips.ipynb](datasets/tips/tips.ipynb) | done |
| titanic | - | planned |
| taxis | - | planned |
| planets | - | planned |
| seaice | - | planned |

## How each notebook is structured

1. **Research questions**
2. **Data overview and cleaning**
3. **Distributions**
4. **Answers to the research questions**
5. **Preparation for modeling**
6. **Conclusions**

## Conventions

- Group comparisons show the mean with a 95% confidence interval.
If the intervals overlap, no effect is claimed.
- Both Pearson and Spearman correlation are reported where the relationship may not be linear.
- Only basic tools: pandas, matplotlib, seaborn, scipy.
- No advanced statistics - these are plain seaborn datasets and the point is EDA.

## Setup

```bash
git clone git@github.com:Paskoi/seaborn_eda_with_visualizations.git
cd seaborn_eda_with_visualizations

python -m venv .venv
source .venv/bin/activate        # Linux / mac
# .venv\Scripts\activate         # Windows
pip install -r requirements.txt
```

Pinned versions are in [requirements.txt](requirements.txt). Notebooks load data with `seaborn.load_dataset`.

## License

[LICENSE](LICENSE).