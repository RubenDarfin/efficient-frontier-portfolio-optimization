# Efficient Frontier Portfolio Optimization

Projet Python d’optimisation de portefeuille fondé sur la théorie moderne du portefeuille de Markowitz.

## Objectif
Construire un portefeuille optimal à partir de données boursières historiques réelles en maximisant le ratio de Sharpe.

## Actifs étudiés
- Apple (AAPL)
- Microsoft (MSFT)
- JPMorgan Chase (JPM)
- Goldman Sachs (GS)
- NVIDIA (NVDA)

## Méthodologie
- Téléchargement des prix historiques avec `yfinance`
- Calcul des rendements journaliers
- Annualisation des rendements et de la matrice de covariance
- Simulation Monte Carlo de 10 000 portefeuilles
- Identification du portefeuille au ratio de Sharpe maximal
- Visualisation de la frontière efficiente et de la répartition optimale

## Résultats
- Rendement annualisé du portefeuille optimal : **42.20%**
- Volatilité annualisée : **29.02%**
- Ratio de Sharpe : **1.39**

## Répartition optimale
- MSFT : 39.56%
- NVDA : 36.79%
- JPM : 20.18%
- GS : 1.76%
- AAPL : 1.71%

## Stack
Python, pandas, numpy, matplotlib, seaborn, yfinance, Jupyter Notebook