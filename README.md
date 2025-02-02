## Description du projet

Ce projet combine deux approches d'apprentissage automatique : l'apprentissage non supervisé pour l'analyse de clusters et l'apprentissage supervisé pour la prédiction de buts en football. Il a été réalisé dans le cadre du cours Science des Données 1 à l'Université Paul Valéry Montpellier III, avec le logiciel Orange Data Mining.

## Auteurs :

### Anthony Combes–Aguéra (Classification non supervisée)

### Wassim Harraga (Classification supervisée)

Présenté à M. Arnaud Sallaberry, Département Mathématiques, Informatique Appliquées.

## Apprentissage non supervisé : Clustering des thématiques de reportages

### Objectif : 

Analyser les thèmes des reportages les plus représentés sur différentes chaînes de télévision entre septembre 2018 et septembre 2020.

### Données :

#### Source : data.gouv.fr

#### Variables : 2 qualitatives (mois, thématique), 5 quantitatives (nombre de sujets par chaîne)

#### Nettoyage des données : suppression des variables inutiles, harmonisation des types et filtrage des dates

## Apprentissage supervisé : Prédiction des buts en football

### Objectif :

Prédire le nombre de buts marqués par un joueur en 2017 à partir des statistiques de 2016.

### Données :

#### Source : Kaggle (Top Football Leagues Scorers Dataset)

#### Variables : 5 qualitatives (joueur, pays, club, ligue, année), 10 quantitatives (buts, tirs, passes, xG, etc.)

#### Nettoyage des données : filtrage sur l'année 2016, création d'une variable cible (Category Goals)
