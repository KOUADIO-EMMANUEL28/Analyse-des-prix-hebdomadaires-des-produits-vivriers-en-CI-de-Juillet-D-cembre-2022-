# Analyse-des-prix-hebdomadaires-des-produits-vivriers-en-CI-de-Juillet-D-cembre-2022-


## Table des matières

-[Description](#description)

-[Sources des données](#sources-des-données)

-[Outils](#ouils)

-[Préparation des données](#préparation-des-données)

-[Analyse exploratoire des données](#analyse-exploratoire-des-données)

-[Analyse des données](#analyse-des-données)

-[Résultats](#résultats)

-[Bon à savoir](#bon-à-savoir)


## Descriprion

Ce projet d'analyse des données a pour but de mettre en évidence l'évolution des prix des produits vivriers en fonction de divers facteurs tels que la disponibilité, le lieu et la catégorie.


### Source de des données
Le datatest utilisé pour cette analyse est le fichier "prix-hebdomadaires-des-produits-vivriers-de-cote-divoire.csv", telechargé sur le site de l'Agence National de Statistiques ANSAT

### Outils
-Rstudio pour le nettoyage et l'analyse des données

-PowerBi pour la création de rapports

#### Préparation des données

Nous avons suivi cette démarche

1.Chargement et inspection des données

2.Suppression des valeurs manquantes

3.Suppression des doublons

#### Analyse exploratoire des données

L'analyse exploratoire des données consistait à explorer les données afin de répondre à des questions clés comme:

-Comment les prix des produits prix évoluent ils  hebdomadairement?

-Comment évoluent les prix en fonction de la catégorie du produit?

-Comment les prix des produits évoluent ils en fonction de leur disponibilité?

-Comment évoluent les prix en fonction du Lieu?

#### Analyse des données
Quelques codes intéressant que de nous avons utilisé avec Rstudio

```rstudio
filter()
select()
mutate()
arrange()
distinct()
```

#### Résultats

Evolution globale du prix moyen




Evolution du prix par catégorie
<img width="851" height="475" alt="image" src="https://github.com/user-attachments/assets/36e29cf2-30cb-413b-95c1-c5b12861043d" />

<img width="863" height="476" alt="prix lieu temps" src="https://github.com/user-attachments/assets/eff9413f-dfd5-4259-b2a8-b490d4575e5a" />


Evolution du prix selon la disponibilité




Evolution du prix selon le Lieu

#### Bon à savoir

1. Nous avons supprimé tous les zéros et les valeurs manquantes dans la colonnes des prix car cela aurait influencé grandement les résultats ,le faisant nous avons perdu une partie des données. Néanmoins ces résultats donne une vision d'ensemble.

2. Les prix sont en FCFA

3. Les produits sont vendus par Kg, donc le prix représente le prix du Kg.



















