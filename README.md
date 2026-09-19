
# ☕ Analyse Exploratoire des Ventes de Café (EDA)

Ce projet présente une analyse exploratoire complète (EDA) d'un jeu de données de ventes de café en utilisant Python. L'objectif est d'identifier les comportements des consommateurs et de formuler des recommandations business.

## 🛠️ Technologies & Bibliothèques utilisées
* **Python**
* **Pandas** (Nettoyage, manipulation et agrégation des données via `groupby` et `agg`)
* **Seaborn / Matplotlib** (Visualisation des données)

## 📊 Principaux Insights
* **Produits phares :** Les boissons composées avec du lait (*Americano with Milk*, *Latte*) dominent largement les ventes par rapport aux boissons plus simples.
* **Paradoxe du prix :** L'article le moins cher (*Espresso*) enregistre paradoxalement le plus faible volume de ventes, prouvant que les clients privilégient la qualité ou le type de boisson au prix brut.
* **Modes de paiement :** Prédominance écrasante du paiement par carte bancaire (~97,5% des transactions).

## 💡 Recommandations Stratégiques
1. **Gestion des stocks :** Assurer un réapprovisionnement prioritaire en lait pour éviter les ruptures sur les produits les plus demandés.
2. **Maintenance :** Garantir la disponibilité absolue du terminal de paiement par carte, indispensable pour la quasi-totalité de la clientèle.
