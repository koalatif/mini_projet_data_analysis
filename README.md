# Mini Projet: Data Processing - Data Viz

## Description
Ce projet vise à analyser des données géographiques du Burkina Faso, en se concentrant sur le téléchargement, le prétraitement, l'exploration et la visualisation des données de localités.

## Étapes du Projet

1. **Identification du code ISO**  
   - Code ISO du Burkina Faso : `BF`.

2. **Téléchargement des données**  
   - Source : [GeoNames](https://download.geonames.org/export/dump/BF.zip).  
   - Fichier extrait : `BF.txt`.

3. **Prétraitement et filtrage**  
   - Colonnes conservées :  
     - `ID` (identifiant)  
     - `location_name` (nom du lieu)  
     - `lat` (latitude)  
     - `long` (longitude).  
   - Sauvegarde : `burkina_location.csv`.

4. **Exploration des données**  
   - Recherche des localités contenant "Gounghin" (10 résultats).  
   - Filtrage des localités dont le nom commence par A à P (8306 résultats).  
   - Calcul des coordonnées minimales :  
     - Latitude minimale : `5.2161` (Komoé).  
     - Longitude minimale : `-5.6597` (Banifing).  
   - Filtrage des lieux avec `lat >= 11` et `long <= 0.5` (9466 résultats).

5. **Création d'un fichier Excel**  
   - Fichier généré : `mini_projet.xlsx`.  
   - Feuilles incluses :  
     - `Gounghin` : 10 lignes.  
     - `A_to_P` : 8306 lignes.

## Fichiers Générés
- `burkina_location.csv` : Données filtrées des localités.  
- `gounghin.csv` : Résultats de la recherche "Gounghin".  
- `mini_projet.xlsx` : Fichier Excel contenant les feuilles de travail.  

## Technologies Utilisées
- Python  
- Pandas  
- OpenPyXL  
- GeoNames API  

## Auteur
KOALA Valentin
