# Nettoyage et Exploration des Données Open Food Facts

## Contexte du Projet

Le projet concerne l'amélioration de la base de données Open Food Facts, un référentiel open-source permettant aux utilisateurs d’accéder à des informations sur la qualité nutritionnelle des produits alimentaires. L'agence Santé publique France a confié à l'entreprise le développement d'un système de suggestion ou d'auto-complétion pour aider les utilisateurs à remplir la base de données de manière plus précise et efficace.

Actuellement, l'ajout de produits dans la base de données nécessite que les utilisateurs remplissent plusieurs champs textuels et numériques, ce qui peut entraîner des erreurs de saisie et des valeurs manquantes. Le projet initial consiste donc à nettoyer et explorer le jeu de données existant pour évaluer la faisabilité de cette application.
Objectifs du Projet

L'objectif principal est de nettoyer et d’explorer le jeu de données afin de préparer le terrain pour la création d'un système de suggestion d'auto-complétion des champs. Les tâches à accomplir incluent :
- Identification des variables pertinentes : Repérer les variables nécessaires pour le traitement et la suggestion des valeurs manquantes.
- Nettoyage des données : Mettre en évidence et traiter les valeurs manquantes et aberrantes, en utilisant au moins trois méthodes adaptées.
- Automatisation des traitements : Développer des outils pour automatiser les processus de nettoyage, de manière à ce que le système fonctionne même après des modifications légères de la base de données (par exemple, l'ajout de nouvelles entrées).
- Visualisation des données : Produire des graphiques et analyses univariées pour mieux comprendre les comportements des variables.
- Création de variables et analyse multivariée : Créer de nouvelles variables pertinentes et effectuer des tests statistiques pour vérifier la significativité des résultats.
- Évaluation de la faisabilité de l'application : Analyser la faisabilité technique du système d'auto-complétion.

## Données

Le jeu de données utilisé provient de Open Food Facts, une base de données libre et ouverte qui contient des informations détaillées sur des produits alimentaires. Les champs de données sont organisés en quatre sections principales :
- Informations générales : Nom du produit, date de modification, etc.
- Tags : Catégorie du produit, localisation, origine, etc.
- Ingrédients et additifs : Liste des ingrédients et additifs éventuels.
- Informations nutritionnelles : Quantités de nutriments pour 100 grammes du produit.

Le jeu de données est disponible en téléchargement à partir du site officiel de Open Food Facts, et les définitions des variables sont accessibles à l'adresse suivante : Définitions des variables.

## Méthodologie

L’analyse se déroule en plusieurs étapes clés :

Préparation des données :
- Identification des variables pertinentes pour la suggestion des valeurs manquantes.
- Traitement des valeurs manquantes en utilisant différentes méthodes, comme l'imputation, la suppression ou l'utilisation de valeurs par défaut.
- Détection et traitement des valeurs aberrantes dans les variables sélectionnées.
- Automatisation des processus de nettoyage afin de garantir leur efficacité en cas de modifications futures du jeu de données.

Exploration des données :
- Réalisation d'une analyse univariée pour chaque variable, en visualisant leur distribution et comportement à l’aide de graphiques adaptés (boxplots, histogrammes, diagrammes circulaires, etc.).
- Analyse des données manquantes et des modèles potentiels pour leur imputation.

Création de nouvelles variables et analyse multivariée :
- Utilisation d’analyses multivariées pour créer de nouvelles variables permettant d’améliorer la qualité de l’information.
- Application de tests statistiques pour vérifier la significativité des variables créées ou sélectionnées.

Rédaction d'un rapport d’exploration :
- Présentation des résultats obtenus, de l'état de la base de données et de la faisabilité de la mise en place d’un système de suggestion pour les champs manquants.
- Conclusion sur la viabilité technique et fonctionnelle du projet d'auto-complétion.

Respect du RGPD :
Bien que les données ne contiennent pas de données personnelles, une évaluation de la conformité avec les principes du RGPD est effectuée. Un rapport sera fourni pour expliquer comment le projet respecte les grands principes du RGPD, et des recommandations seront faites pour répondre aux préoccupations du public.

## Outils et Technologies

L’analyse a été réalisée avec les outils et bibliothèques suivants :
- Pandas pour la manipulation des données.
- Matplotlib et Seaborn pour la création de graphiques et la visualisation.
- Scikit-learn pour les méthodes d’imputation et les tests statistiques.
- NumPy pour le calcul des statistiques de base.

## Résultats et Application

À l'issue de ce projet, les résultats permettront de déterminer la faisabilité technique et fonctionnelle d'un système d'auto-complétion pour la base de données Open Food Facts. Le rapport final inclura des recommandations sur les améliorations possibles de la base de données et sur la manière dont un tel système pourrait être déployé pour simplifier le processus d'ajout de produits, tout en respectant les principes du RGPD.
