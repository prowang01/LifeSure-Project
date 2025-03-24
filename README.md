# LifeSure-Project
Project in Explainability AI (WANG Prosper, VANSIELEGHEM Antoine, DUONG Wendy, SHAMIEH George, ESILV DIA6)

Projet d’analyse et de modélisation de la consommation énergétique en France métropolitaine à partir de données ouvertes.

## 📊 Objectifs
- Étudier la consommation énergétique par région et par mois
- Analyser l’impact de la météo sur la consommation
- Prédire la consommation future
- Détecter des anomalies et regrouper les régions par profil

## 🧠 Modèles utilisés

| Modèle              | But                                                                 |
|---------------------|----------------------------------------------------------------------|
| 🔹 Régression        | Prédire la consommation à partir des températures                   |
| 🔹 Séries temporelles (Prophet) | Prévoir la consommation mensuelle par région sur 12 mois    |
| 🔹 Clustering (KMeans) | Regrouper les régions selon température et consommation             |
| 🔹 Anomalies (Isolation Forest) | Détecter des pics ou baisses anormales de consommation     |

## 📁 Contenu du projet

- `Consommation_Production.ipynb` → Notebook principal contenant toutes les modélisations
- `Temperatures_quotidiennes_departmentales.ipynb` → Préparation des données météo
- `df_anomalies.csv`, `df_clust.csv`, etc. → Fichiers intermédiaires pour Power BI
- `Projet_ExplainabilityAI.pdf` → Cahier des charges / document de spécifications
- `PowerBI_Visuals.pbix` → (à venir) Tableau de bord interactif Power BI

## 🛠️ Données utilisées

- Consommation énergétique (RTE via data.gouv.fr)
- Températures journalières par département (Météo France / open-meteo.com)
- Données fusionnées, nettoyées et agrégées par mois

## 🔍 Pistes futures

- Intégrer des données socio-économiques (revenus, logement, densité)
- Améliorer les modèles avec des features plus riches
- Développer un tableau de bord dynamique (Power BI)

---

**📌 Réalisé dans le cadre du cours "Explainability & AI", ESILV (2025)**  
