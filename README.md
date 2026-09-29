# Finance & Business Analytics Series

A series of short, practical data analysis projects that answer real business questions with sales data. Each project goes with a LinkedIn post and is written to be educational: every notebook explains *why* each step is taken, not just *what* the code does.

Each project follows the same arc:

1. **A business question.** Something a manager or finance team would actually ask.
2. **Exploratory analysis.** Clean the data and find the evidence.
3. **Feature engineering.** Turn raw columns into business meaning (unit economics, customer behaviour, what-if scenarios).
4. **Machine learning.** A quick model to test and strengthen the claim.
5. **A recommendation.** What the business should do about it.

## Projects

| # | Project | Business question | Headline finding |
|---|---|---|---|
| 01 | [Discount Impact Analysis](01-discount-impact/) | Do discounts actually make the business money, or just inflate revenue while eating profit? | Every loss-making order carried a discount. Margins turn negative at a ~25% discount, and $567K was given away in discounts to earn $286K in profit. |

## Data

The projects use the **Sample Superstore** dataset, downloaded from **Kaggle**: [Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final). It was originally published by Tableau as a sample dataset. It holds 9,994 order lines from a fictional US office-supplies retailer (2014–2017), with sales, quantity, discount, profit, product category, region, customer segment and order/ship dates.

The CSV is **not included in this repository** (the `data/` folders are git-ignored). To run a notebook:

1. Download the CSV from the [Kaggle page](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final).
2. Save it as `data/Sample - Superstore.csv` inside the project folder, e.g. `01-discount-impact/data/Sample - Superstore.csv`.

## Tools

Python · pandas · NumPy · Matplotlib · SciPy · scikit-learn · Jupyter

```bash
pip install pandas numpy matplotlib scipy scikit-learn
```

## Author

**Ofor Chukwuebuka Emmanuel** · [LinkedIn](https://www.linkedin.com/in/ebuka-enterprises)
