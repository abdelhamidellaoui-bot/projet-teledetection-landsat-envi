Traitement d'images Landsat 5 TM sous ENVI

Travaux pratiques de Télédétection des Ressources Naturelles et Environnement – IAV Hassan II, Rabat (filière IDSA), année universitaire 2025-2026. Encadrant : M. Chikhaoui Mohammed.
Auteur : Abdelhamid Ellaoui 

Objectif
Mettre en œuvre une chaîne complète de traitement d'une image satellitaire, de l'image brute à la carte thématique : prétraitement, classifications supervisée et non supervisée, évaluation de la précision et calcul d'indices de végétation.
Données et outils
•	Image : Landsat 5 TM (scène path 201 / row 035, juin 2010), bandes 1 à 5 et 7
•	Zone d'étude : nord du Maroc, région de Tétouan-Larache
•	Logiciel : ENVI 5.1

Les bandes Landsat brutes ne sont pas incluses dans ce dépôt en raison de leur taille. Elles sont téléchargeables gratuitement sur USGS EarthExplorer.
Méthodologie
1.	Visualisation : composition colorée en vraies couleurs
2.	Calibration radiométrique : conversion en réflectances, puis analyse des profils spectraux (végétation, eau, sol nu, bâtiments)
3.	Correction atmosphérique
4.	Découpage et correction géométrique, puis délimitation de la zone d'étude
5.	Régions d'intérêt (ROI) : zones d'entraînement et de validation (eau, végétation, sol, bâtiments)
6.	Classifications supervisées : Parallélépipède et Maximum de Vraisemblance
7.	Classifications non supervisées : ISODATA et K-means (5 classes)
8.	Évaluation de la précision : matrice de confusion et coefficient Kappa
9.	Signatures spectrales par classe
10.	Indices de végétation : NDVI et RVI
11.	Habillage cartographique et classification semi-supervisée (hybride)

Résultats principaux
Méthode	Précision globale	Kappa
Parallélépipède	97,22 %	0,9632
Maximum de Vraisemblance	100 %	1,0000
L'évaluation repose sur 108 pixels de validation (environ 20 % des ROI) : ces scores sont donc à interpréter avec prudence, car l'échantillon est limité.
Aperçu
	
Zone d'étude
Aperçu de la scène
Zone d'étude	Aperçu de la scène Landsat
Maximum de vraisemblance
Parallélépipède
Classification Maximum de Vraisemblance	Classification Parallélépipède
ISODATA
K-means
Classification ISODATA	Classification K-means
Semi-supervisée
NDVI
Classification semi-supervisée	NDVI
Contenu du dépôt
•	rapport/ : rapport complet du TP (PDF)
•	images/ : cartes et profils spectraux issus des traitements

Contact
Abdelhamid Ellaoui – Étudiant ingénieur IDSA, IAV Hassan II – abdelhamid.ellaoui@iav.ac.ma
