# Analyse des catastrophes naturelles avec R – Base EM-DAT

## Contexte
Ce projet repose sur l’exploitation des données issues de la base **EM-DAT (Emergency Events Database)**, développée par le CRED (Université catholique de Louvain), qui recense les catastrophes naturelles et technologiques dans le monde depuis 1900.

L’étude porte sur deux pays : **Algérie** et **Chili**, à partir de fichiers de données distincts fournis dans le cadre pédagogique.

## Objectifs du projet
- Lire et structurer des données complexes issues de fichiers Excel
- Identifier et gérer les données manquantes
- Produire des synthèses statistiques automatisées
- Analyser l’évolution temporelle des catastrophes
- Visualiser les résultats à l’aide de graphiques pertinents
- Manipuler des dates et durées à partir de formats hétérogènes
- Mettre en œuvre une analyse reproductible sous R

## Données utilisées
- Base EM-DAT (1900–2025)
- Données spécifiques à deux pays : Algérie et Chili
- Variables relatives aux types de catastrophes, dates de début et de fin, durées, sous-groupes et localisations

## Méthodologie

### Chargement et exploration des données
- Lecture de fichiers Excel avec le package `readxl`
- Identification des feuilles, des variables et des dimensions
- Vérification de la présence de données manquantes
- Contrôle de la cohérence des pays étudiés

### Analyse descriptive
- Construction de tables de contingence par type de catastrophe et par année
- Étude de l’évolution temporelle des catastrophes naturelles et technologiques
- Comparaison graphique des fréquences annuelles

### Analyse des catastrophes naturelles
- Étude des sous-groupes de catastrophes naturelles
- Analyse détaillée des types de catastrophes par sous-groupe
- Représentations graphiques en proportions et comparaisons croisées

### Analyse temporelle
- Construction de variables temporelles basées sur l’epoch Unix
- Calcul des dates de début et de fin des événements
- Calcul des durées des catastrophes
- Analyse de la distribution des durées et identification des outliers

### Séquences de catastrophes
- Identification de séquences d’événements liés dans le temps
- Regroupement d’événements proches selon un délai fixé
- Analyse des dépendances temporelles entre catastrophes

### Comparaison internationale
- Reproduction des analyses pour le second pays
- Comparaison synthétique des résultats entre l’Algérie et le Chili

## Résultats
- Visualisations claires de l’évolution des catastrophes par type
- Analyse comparative entre deux pays aux profils géographiques distincts
- Mise en évidence de différences structurelles dans la nature et la durée des événements
- Export automatique de graphiques et de données nettoyées

## Outils et packages utilisés
- R
- readxl
- tidyverse
- ggplot2
- lubridate

## Compétences développées
- Analyse de données sous R
- Nettoyage et gestion de données manquantes
- Manipulation avancée des dates et durées
- Visualisation statistique
- Automatisation de traitements analytiques
- Rédaction de code commenté et reproductible

## Fichiers inclus
- Notebook Jupyter (noyau R) ou scripts R commentés
- Graphiques exportés au format PDF
- Fichiers CSV de données enrichies

