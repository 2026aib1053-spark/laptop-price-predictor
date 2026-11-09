# Laptop Price Prediction

Predicts the price of a laptop from its specifications (brand, RAM, storage, screen, CPU, GPU, weight) using **Linear Regression** (scikit-learn).

`AI101 Mini-Project` `Team 85` `Python 3.11+`

## Team and roles

| Member | Entry no. | Role |
|---|---|---|
| vutukuru vighnesh koundinya | 2026aib1098 | Documentation lead |
| madhav shri krishan sharma | 2026aib1053 | Execution lead |
| masina veerendra kumar | 2026eeb1376 | PPT lead |
| deependra kumar saini | 2026eeb1340 | Video lead |

All four members contributed code (see commit history).

## Project structure

```
laptop-price-predictor/
├── data/laptop_data.csv       # 1,303 laptops, 11 columns
├── laptop_price_prediction.ipynb         # cleaning, EDA, Linear Regression, evaluation
├── file:///C:/Users/User/Downloads/Laptop_Price_Prediction_Group_85_Updated.pdf      # 5-slide presentation
├── requirements.txt
└── README.md
```

## Setup

Tested on Python 3.11 (Windows, macOS, Ubuntu).

```bash
git clone <repo-url>
cd laptop-price-predictor
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
```

## How to run

1. Start Jupyter: `jupyter notebook`
2. Open `laptop_price.ipynb`
3. Click **Kernel → Restart & Run All** (Run → Run All Cells in JupyterLab)

## Expected output

- Cleaned data, EDA plots, correlation heatmap
- Test R² of about 0.77, MAE of about ₹12,600, RMSE of about ₹18,400
- Price histogram, scatter plot, correlation heatmap, actual-vs-predicted plot and a learning curve
- Expected runtime: about 1 minute

## Links

- Slides (5): `docs/team_slides.pdf`
- Video: `<paste YouTube / Drive link>`

## AI-use disclosure

- Claude: drafted the first version of the notebook code; the team reviewed, ran and understood it, and checked the results.
- (Edit to match what your team actually used.)
