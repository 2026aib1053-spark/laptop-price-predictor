# Laptop Price Prediction

Predicts the price of a laptop from its specifications (brand, RAM, storage, screen, CPU, GPU, weight) using Linear Regression (pandas, matplotlib, seaborn, scikit-learn).

`AI101 Mini-Project` `Team [85]` `Python 3.14.6`

## Team and roles

| Member | Entry no. | GitHub | Role |
|---|---|---|---|
| [vutukuru vighnesh koundinya] | [2026aib1098] | [2026aib1098] | Documentation lead |
| [madhav shri krishan sharma] | [2026aib1053] | [2026aib1053-spark](https://github.com/2026aib1053-spark) | Execution lead |
| [masina veerendra kumar] | [2026eeb1376] | [2026eeb1376] | PPT lead |
| [deependra kumar saini] | [2026eeb1340] | [saini8356] | Video lead |

All four members contributed code (see commit history).

## Project structure

```
laptop-price-predictor/
├── data/
│   └── laptop_data.csv         # 1,303 rows x 12 columns ([dataset name and link])
├── src/
│   └── laptop_price_prediction.ipynb           # entry point: preprocessing, training, evaluation, plots
├── Laptop_Price_Prediction_Group_85_Updated.pdf         # 5-slide presentation
├── requirements.txt            # pinned library versions
├── .gitignore
└── README.md
```

## Setup

Tested on Python [3.14.6] ([Windows]).

```bash
git clone [github.com/2026aib1053-spark/laptop-price-predictor](https://github.com/2026aib1053-spark/laptop-price-predictor)
cd laptop-price-predictor
python -m venv venv
# Windows:   venv\Scripts\activate
# Linux/Mac: source venv/bin/activate
pip install -r requirements.txt
```

## How to run

1. Run `jupyter notebook laptop_price.ipynb`, then choose Kernel -> Restart and Run All (in VS Code: open `laptop_price.ipynb` and click Run All).
2. The notebook prints MAE, MSE, RMSE and R-squared on the test set and shows the plots.
3. Expected runtime: under 1 minute.

Result: MAE 12,565, RMSE 18,397, R² 0.765 (test set). Linear Regression explains about 77% of the variation in laptop prices; train R² is 0.778, so the model is not overfitting.



## Links

Slides (5): [file:///C:/Users/User/Downloads/Laptop_Price_Prediction_Group_85_Updated.pdf](Laptop_Price_Prediction_Group_85_Updated.pdf) - Video: [paste unlisted YouTube or Drive link]

## AI-use disclosure

- Claude: drafted the first version of the README; the team write, reviewed, ran and checked the code and results.
- No AI was used to generate the dataset or the results.
