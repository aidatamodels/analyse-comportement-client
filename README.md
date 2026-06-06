# 📊 Décoder le Comportement Client : De la Régression au Test A/B

Bienvenue dans ce projet d'analyse de données axé sur la valorisation de l'information client. Ce dépôt propose une démarche analytique complète, conçue comme une passerelle didactique entre la rigueur de la théorie statistique et l'application stratégique d'affaires. 

L'objectif est de démontrer comment une architecture de données solide permet de dépasser la simple intuition managériale pour asseoir les prises de décision sur des preuves empiriques et des modèles mathématiques robustes.

---

## 🎯 Architecture de l'Analyse

Ce projet déconstruit le comportement consommateur à travers cinq piliers analytiques fondamentaux. Chaque étape du code est accompagnée d'explications pédagogiques (analogies et concepts vulgarisés) pour rendre les résultats intelligibles tant pour les profils techniques que pour les décideurs d'affaires.

1. **📈 L'Analyse de Régression (Prédiction) :** Modélisation mathématique de l'élasticité de la dépense par rapport au revenu (calcul et interprétation du $R^2$).
2. **📅 L'Analyse de Cohortes (Dynamique Temporelle) :** Cartographie des vagues d'acquisition historiques pour évaluer la pérennité et la santé de la croissance de l'entreprise.
3. **🧩 L'Analyse Typologique (Clustering K-Means) :** Segmentation algorithmique non supervisée de la base de données visant à découvrir les profils naturels du marché, sans biais cognitif humain.
4. **📉 L'Analyse en Composantes Principales (PCA) :** Réduction de la dimensionnalité multidimensionnelle des achats (compression des données) pour faire émerger des signaux clairs à partir du bruit statistique.
5. **⚖️ Le Test A/B (Rigueur Décisionnelle) :** Validation scientifique de l'efficacité de différentes campagnes marketing via le test d'indépendance du Chi-Deux ($\chi^2$) et l'interprétation stratégique de la P-value.

---

## 💾 Le Jeu de Données

L'analyse repose sur le dataset public **"Customer Personality Analysis"**. Il regroupe les profils détaillés de plusieurs milliers de clients d'une entreprise de vente au détail. 

Les données exploitées couvrent quatre grandes dimensions :
* **Sociodémographique :** Âge, éducation, situation familiale, revenu.
* **Comportement d'achat :** Volume de dépenses réparties par catégories (Vins, Viandes, Produits de Luxe, etc.).
* **Parcours d'acquisition :** Habitudes d'achats (Web, Catalogue, Magasin physique).
* **Réactivité Marketing :** Historique d'acceptation ou de refus face à différentes campagnes de sollicitation.

---

## 🛠️ Technologies et Librairies Utilisées

Ce projet a été développé en Python au sein d'un environnement Jupyter Notebook, en s'appuyant sur les standards de l'industrie pour la Data Science :

* **Manipulation des données :** `pandas`, `numpy`
* **Modélisation & Machine Learning :** `scikit-learn` (LinearRegression, KMeans, PCA, StandardScaler)
* **Tests Statistiques :** `scipy.stats` (chi2_contingency)
* **Visualisation :** `matplotlib`, `seaborn`
* **Acquisition de données :** `kagglehub`

## Licence

Ce projet est distribué sous licence MIT.

La licence MIT autorise l’utilisation, la modification, la distribution et la réutilisation du code, à condition de conserver l’avis de copyright et le texte de la licence.

Voir le fichier [LICENSE](LICENSE) pour plus de détails.

Cette licence s’applique au code source du projet. Les données externes utilisées restent soumises aux conditions d’utilisation de leur source d’origine, notamment Kaggle.

## Auteur

Projet développé par `aidatamodels`.
