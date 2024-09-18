# HakimaTpSpark

## **Description du projet**
Ce projet consiste à analyser les données de deux magasins de produits de cuisine en utilisant **PySpark**. L'objectif est de nettoyer et de préparer les données, puis d'extraire des informations utiles pour améliorer les prises de décisions commerciales.

## **Prérequis**
- **Docker** pour exécuter l'image contenant PySpark.
- **PySpark** (utilisé pour l'analyse des données).
- **Python** 3.x
- **Jupyter Notebook** (ou Google Colab, si vous préférez l'utiliser en ligne).

### **Commande Docker** :

docker run -it -p127.0.0.1:4040:4040 -p127.0.0.1:8888:8888 -v "$(pwd)":/home/jovyan/work/ jupyter/pyspark-notebook:x86_64-spark-3.5.0

**Étapes principales**
Chargement des données :

Les données sont chargées à partir de fichiers CSV et JSON, représentant les ventes de deux magasins.
**Nettoyage des données :**

Suppression des doublons.
Gestion des valeurs manquantes.
Conversion des types de données (par exemple, les prix unitaires en flottants).
Analyse des prix unitaires :

Identification des valeurs extrêmes (outliers) à l'aide de tests de normalité.
Utilisation de méthodes de normalisation (Min-Max) et de standardisation (Z-Score).
Filtrage des valeurs aberrantes :

Filtrage des outliers en appliquant la règle des trois écarts-types autour de la moyenne.
**Agrégation des données :**

Analyse des tendances de vente mensuelles et annuelles.
Identification des produits les plus populaires.
**Visualisation des résultats :**

Utilisation de visualisations pour faciliter la compréhension des données et des tendances clés.
Utilisation
**Clonez ce dépôt GitHub :**
'git clone https://github.com/DH-HUB/HakimaTpSpark.git'

Lancer le projet dans un environnement Docker (si vous utilisez Docker) ou ouvrez-le directement dans Google Colab.

Exécutez les cellules du notebook pour reproduire l'analyse.

Auteur:
Hakima Djermouni - Contributeur principal
Licence
Ce projet est sous licence MIT - voir le fichier LICENSE pour plus de détails.
