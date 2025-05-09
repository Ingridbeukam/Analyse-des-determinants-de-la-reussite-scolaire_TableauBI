# 🎓 Analyse des Déterminants de la Réussite Scolaire – Tableau BI

## 🧾 Description

Ce projet repose sur l’analyse visuelle des données de `student_data` (Kaggle) à l’aide de **Tableau BI**. L’objectif est d’identifier les principaux facteurs influençant les performances académiques des élèves (notes G1, G2, G3) selon leur environnement familial, social, éducatif et comportemental.

Le tableau de bord interactif permet d’explorer dynamiquement les tendances, comparer les sous-groupes d’élèves, et visualiser les corrélations entre différents indicateurs (temps d’étude, soutien familial, consommation d’alcool, etc.).

---

## 🎯 Objectifs

- Identifier les variables déterminantes de la réussite scolaire
- Visualiser l’impact de facteurs sociaux et familiaux sur les notes finales
- Segmenter les élèves selon leur profil académique et comportemental
- Créer un tableau de bord interactif pour une exploration libre des données

---

## 📁 Fichiers inclus

- `Analyse des Déterminants de la Réussite Scolaire-Tableau BI.twb` → Fichier Tableau BI du tableau de bord
- `student_data.csv` → Données d’origine issues de Kaggle
- `screenshots/` → Captures du tableau de bord
- `README.md` → Ce fichier

---

## 🛠️ Outils utilisés

- **Tableau Desktop**
- Nettoyage et préparation des données dans Tableau
- Création de dimensions et mesures personnalisées
- Tableaux de bord avec filtres dynamiques, zones de détail, tris et survols
- Visualisations : nuages de points, histogrammes, courbes, bar charts, boxplots

---

## 📊 KPIs et dimensions analysées

- 📚 Note finale (`G3`) – performance académique principale
- ⏳ Temps d’étude hebdomadaire (`studytime`)
- 🍺 Consommation d’alcool en semaine et week-end (`Dalc`, `Walc`)
- 👪 Niveau d’éducation des parents (`Medu`, `Fedu`)
- ❤️ Soutien familial et scolaire (`schoolsup`, `famsup`)
- 🏫 Activités extrascolaires (`activities`)
- 🔁 Échec passé (`failures`)
- 👤 Sexe, âge, école, statut familial

---

## 💡 Insights dégagés
-Moyenne des résultats finaux (G3) par (sexe, Education des parents, school, address)

-Répartition des notes finales (G3)

-Taux d’échec par école, par genre, par activité

-Moyenne des absences par studytime, romantic, etc.

-Influence du temps de trajet (traveltime) sur la note finale

-Score global et Catégorisation : Élèves faibles / moyens / forts

-Corrélation entre facteurs et performances (G3)

-Consommation d’alcool vs G3

-Moyenne d’absences selon certains facteurs (studytime, romantic, goout)



---
