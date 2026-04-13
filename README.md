# Analyse économétrique — Valeur marchande Liga 2024/25

## Objectif
Identifier les déterminants de la valeur marchande 
des joueurs de football en Liga 24/25 et analyser 
si ces effets varient selon le poste occupé.

## Données
- 359 joueurs de Liga 2024/25
- Sources : Sofascore, FBref, WhoScored, FotMob, Transfermarkt
- Minimum 500 minutes jouées

## Méthode
- 8 modèles de régression OLS distincts par poste
- Tests économétriques : Jarque-Bera, Durbin-Watson, 
  Breusch-Pagan, VIF, F-statistic, tests t

## Résultats
- R² entre 0.483 (latéraux) et 0.790 (avant-centres)

## Outils
Python — pandas, statsmodels, seaborn, sklearn
