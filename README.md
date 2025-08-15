# Mini Projet: Data Processing - Data Viz
## Description du Projet
Ce projet vise à analyser des données géographiques de lieux du Burkina Faso en utilisant les données open source de GeoNames. Il inclut le téléchargement automatique des données, leur traitement, filtrage et visualisation sous différents formats.
## Objectifs

Télécharger et traiter les données géographiques du Burkina Faso
Filtrer et analyser les localités selon différents critères
Créer des exports structurés (CSV, Excel) pour faciliter l'utilisation des données
Effectuer des recherches spécifiques sur les localités

## Installation et Utilisation

Cloner ou télécharger le projet
bashgit clone [url-du-repository]
cd burkina-data-analysis

Installer les dépendances
bashpip install -r requirements.txt

Exécuter le notebook
bashjupyter notebook Data_processing_projet.ipynb


## Fonctionnalités
1. Téléchargement automatique des données

Source : GeoNames.org
Pays : Burkina Faso (Code ISO: BF)
Format : Fichier texte tabulé (TSV)
Contenu : 8306 localités avec coordonnées géographiques

2. Traitement des données

Colonnes extraites :

ID : Identifiant unique de la localité
location_name : Nom de la localité
lat : Latitude
long : Longitude



3. Analyses et filtres disponibles
Recherche spécifique

Localités "Gounghin" : Recherche de tous les lieux contenant "Gounghin"
Résultats : 10 localités trouvées

Filtrage alphabétique

Critère : Localités dont le nom commence par les lettres A à P
Résultats : 8,306 localités sur 11,958 au total (69.5%)


## Fichiers générés
Fichiers CSV

burkina_location.csv : Dataset complet des localités
gounghin.csv : Localités contenant "Gounghin"

Fichier Excel

mini_projet.xlsx avec deux feuilles :

Feuille "Gounghin" : 10 lignes de données Gounghin
Feuille "A_to_P" : 8,306 lignes des localités A-P


Dernière mise à jour : août 2025
Version : 1.0
Auteur : [KOALA Valentin]
