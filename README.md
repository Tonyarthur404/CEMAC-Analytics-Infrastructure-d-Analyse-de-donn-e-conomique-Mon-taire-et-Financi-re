# 🌍 CEMAC Analytics : Infrastructure d'Analyse de Données Économique, Monétaire et Financière

Une plateforme complète de Business Intelligence développée en autonomie pour transformer les données publiques dispersées de la Zone CEMAC en une infrastructure décisionnelle unifiée. Ce projet couvre six mois et demi de collecte, structuration et modélisation de données économiques, financières, monétaires et bancaires sur les six pays de la zone.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Présentation_Vidéo-blue?style=for-the-badge&logo=linkedin)]([À COMPLÉTER])
[![Power BI](https://img.shields.io/badge/Power_BI-Rapport_Interactif-yellow?style=for-the-badge&logo=powerbi&logoColor=black)]([À COMPLÉTER])

---

## 📌 Objectifs du Projet

En tant que Business Analyst et Data Engineer, j'ai construit cette plateforme pour répondre à deux défis réels de la zone CEMAC :

* **Asymétrie informationnelle :** Centraliser des données dispersées entre BEAC, COBAC, FMI, Banque Mondiale, UN Comtrade et Harvest Asset Management dans un référentiel unique.
* **Surveillance de la convergence :** Automatiser le suivi des critères de convergence CEMAC — inflation, dette publique, solde budgétaire, réserves de change.
* **Gouvernance augmentée par l'IA :** Intégrer des modèles prédictifs (Prophet, XGBoost) pour projeter les trajectoires économiques sans jamais se substituer à la décision humaine.
* **Analyse bancaire et financière :** Suivre les indicateurs prudentiels COBAC, le marché des titres publics, l'inclusion financière et le Mobile Money.

---

## 📊 Architecture des Tableaux de Bord

| Dashboard | Description | Indicateurs clés |
| :--- | :--- | :--- |
| ** Accueil** | Page d'entrée avec navigation vers les 11 tableaux de bord. | Navigation |
| ** Macroéconomie** | Vue consolidée PIB, inflation, secteur extérieur des 6 pays. | PIB nominal, Inflation IPC |
| ** Finances Publiques** | Recettes, dépenses, soldes budgétaires par pays. | Solde Budgétaire % PIB |
| ** Dette** | Encours de dette publique et ses composantes. | Dette Pub. % PIB |
| ** Monétaire & Crédit** | Masse monétaire, crédit à l'économie, TIAO. | M2, Crédit Éco |
| ** Bancaire / COBAC** | Supervision prudentielle des banques commerciales et EMF. | NPL, PNB, Spread TEG/TIAO |
| ** Inclusion Financière** | Mobile Money, bancarisation, GIMAC, SYSTAC. | Taux de bancarisation |
| ** Marché des Titres** | Émissions BTA/OTA par pays et maturité. | Taux de réalisation |
| ** Secteur Extérieur** | Commerce extérieur par filière et partenaire. | Exports/Imports |
| ** Alertes & Convergence** | Suivi automatisé des 4 critères de convergence CEMAC. | Score de Risque Composite |
| ** IA & Prévisions** | Projections Prophet et XGBoost sur 3 horizons. | Prévisions H1/H2/H3 |

---

## 📸 Aperçu des Tableaux de Bord

###  Page d'Accueil & Navigation
![Page d'accueil](Screenshot/home_page.png)

###  1. Macroéconomie
*Vue consolidée PIB, inflation et comparaison des seuils de convergence.*
![Macroéconomie](Screenshot/macroeconomie.png)

###  2. Bancaire / COBAC
*Supervision prudentielle et indicateurs de risque bancaire.*
![Bancaire COBAC](Screenshot/bancaire_cobac.png)

###  3. Alertes & Convergence
*Matrice de convergence et journal d'alertes automatisées.*
![Alertes Convergence](Screenshot/alertes_convergence.png)

###  4. IA & Prévisions
*Matrice Prophet vs XGBoost avec intervalles de confiance.*
![IA Prévisions](Screenshot/ia_previsions.png)

---

## 🔍 Enseignements Stratégiques

* **Deux modèles, deux lectures :** Prophet capture la tendance temporelle avec intervalles de confiance explicites ; XGBoost capture les interactions croisées entre indicateurs — ensemble, ils offrent une vision robuste plutôt qu'un chiffre unique trompeur.
* **La rigueur prime sur la vitesse :** Le moteur d'alertes distingue strictement les données réelles constatées (BEAC/COBAC) des projections (FMI), pour ne jamais confondre un risque anticipé avec un risque avéré.

---

## 🚀 Perspectives d'évolution

Le projet est conçu pour évoluer avec les besoins de la zone. Les prochaines étapes envisagées incluent l'enrichissement continu des sources de données, l'amélioration de la robustesse des modèles prédictifs, et l'extension progressive de la couverture fonctionnelle de la plateforme.

---

## 🛠️ Stack Technique & Compétences

* **Python :** Scripts de collecte, transformation et chargement (ETL) 
* **PostgreSQL :** Entrepôt de données 
* **Prophet & XGBoost :** Modélisation prédictive multi-horizons.
* **Power BI & DAX :** 10 tableaux de bord, mesures de convergence, moteur d'alertes visuel.
* **Streamlit :** Interface publique BDEMF (Base de Données Économique, Monétaire et Financière).
* **Orchestration :** Pipeline automatisé, de la collecte à l'entraînement des modèles, en une seule exécution.

---

*Projet indépendant — Tony Arthur KENMOE KEMBOU, Business Analyst & Data Engineer, Yaoundé.*
*Certifié Codebasics — Data Analytics Bootcamp 5.0.*
