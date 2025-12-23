# Applied Machine Learning Projects

A collection of applied machine learning notebooks and small utilities covering
time series, NLP, computer vision, and tabular regression.

## Projects

| Project                                   | Focus                                        | Primary Artifacts                                                                                                                                     |
| ----------------------------------------- | -------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- |
| `air-pollution-prediction`                | PM2.5 time-series forecasting (RNN, SARIMAX) | `air-pollution-prediction/notebook.ipynb`, `data/LSTM-Multivariate_pollution.csv`                                                                     |
| `automated-keyword-extraction`            | NLP keyword extraction from articles         | `automated-keyword-extraction/Automated_Keyword_Extraction.ipynb`                                                                                     |
| `car-sales-prediciton`                    | Car sales regression with multiple ML models | `car-sales-prediciton/Car_Sales_Prediction.ipynb`, `car-sales-prediciton/Car_Sales_Prediction(Using Deep Learning).ipynb`                             |
| `football-player-market-value-prediction` | Player market value prediction (NN)          | `football-player-market-value-prediction/Prediction of Football Player's MarketValue.ipynb`, `football-player-market-value-prediction/players_21.csv` |
| `skin-cancer-detection`                   | Image-based skin lesion classification       | `skin-cancer-detection/skincFinal.ipynb`                                                                                                              |

## Quick Start

```bash
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Open any notebook under the project folders:

```bash
jupyter notebook
```

## Repository Layout

```
.
├── air-pollution-prediction/
├── automated-keyword-extraction/
├── car-sales-prediciton/
├── football-player-market-value-prediction/
├── skin-cancer-detection/
├── data/
├── utils/
├── requirements.txt
└── README.md
```

## Data Notes

- `data/LSTM-Multivariate_pollution.csv` supports the air pollution notebook.
- `football-player-market-value-prediction/players_21.csv` is used by the
  player market value notebook.

If you store additional large datasets locally, add them to `.gitignore` or keep
them outside the repo.

## Environment

Core dependencies are listed in `requirements.txt` and include
`scikit-learn`, `tensorflow`, `statsmodels`, and `nltk`.

## License

MIT License
