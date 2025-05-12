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

## ✅ Conclusion de l’analyse

L’analyse des données issues du dataset student_data révèle que la réussite scolaire (note G3) des élèves est influencée par une combinaison de facteurs personnels, familiaux et comportementaux, bien plus qu’un seul élément isolé.

### 🎓 Facteurs familiaux

Niveau d’éducation des parents : On observe une augmentation progressive des moyennes G3 avec le niveau d'éducation du père. Une tendance similaire, bien que plus modérée, est visible du côté de la mère.

Taille de la famille : Les élèves issus de petites familles (≤3 membres) affichent une moyenne G3 légèrement supérieure (≈11) à ceux issus de familles plus nombreuses (>3 membres) (≈10.17).

Profession des parents : Les élèves dont les parents travaillent dans les domaines de la santé ou de l’enseignement tendent à avoir de meilleures moyennes.

Responsable légal : Les élèves gardés par leur père ou mère ont des moyennes plus élevées (~10.6 et ~10.4) que ceux gardés par d’autres personnes (~9.03), effet renforcé selon la taille de la famille.

### 🕒 Facteurs comportementaux

Temps d’étude hebdomadaire : Les meilleurs résultats sont atteints avec un temps d’étude modéré (5–10 heures/semaine). Un temps d’étude très élevé n’entraîne pas nécessairement une amélioration des performances.

Accès à Internet : Les élèves disposant d’un accès à Internet à la maison ont une moyenne G3 supérieure (10.6) comparée à ceux qui n’y ont pas accès (9.4).

### 🍷 Facteurs sociaux et autres

Consommation d’alcool (semaine ou week-end) : Aucun lien clair ou constant n’est observé entre la consommation d’alcool et les performances scolaires dans ce dataset.

Activités extrascolaires : Les activités en dehors de l’école n'ont pas non plus montré de corrélation forte avec la moyenne finale.

Zone d’habitation : Les élèves vivant en zone urbaine obtiennent en moyenne une note G3 plus élevée (10.6) que ceux vivant en zone rurale (9.5).

Distribution générale des notes : L’histogramme montre que la majorité des élèves (plus de 60) obtiennent une moyenne G3 comprise entre 10 et 12.

### 🧠 Conclusion générale
Les résultats indiquent que la réussite scolaire est multifactorielle : un soutien familial solide, un temps d’étude équilibré, un bon cadre de vie (urbain, connecté) et une présence parentale directe sont des leviers favorables à de meilleures performances académiques.

### 📬 Contact
Tu peux me contacter via ingridbeukam@gmail.com ou LinkedIn https://www.linkedin.com/in/ingrid-madjougang-beukam/ pour toute question ou suggestion.
