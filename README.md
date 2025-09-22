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

Ce projet d'analyse des données a pour but de mettre en évidence l'évolution des prix des produits vivriers(par Kg) en fonction de divers facteurs tels que la disponibilité, le lieu et la catégorie.


### Source de des données
Le datatest utilisé pour cette analyse est le fichier "prix-hebdomadaires-des-produits-vivriers-de-cote-divoire.csv", telechargé sur le site de l'Agence National de Statistiques ANSAT

### Outils
-Rstudio pour le nettoyage et l'analyse des données

-PowerBI pour la création de rapports

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
<img width="851" height="475" alt="image" src="https://github.com/user-attachments/assets/36e29cf2-30cb-413b-95c1-c5b12861043d" />

<img width="863" height="476" alt="prix lieu temps" src="https://github.com/user-attachments/assets/eff9413f-dfd5-4259-b2a8-b490d4575e5a" />


Evolution du prix selon la catégorie

<img width="718" height="253" alt="prix KTG tbl" src="https://github.com/user-attachments/assets/c0926aeb-3265-4eac-8052-1237201e28e9" />



<img width="517" height="448" alt="prix KTG" src="https://github.com/user-attachments/assets/02a3280a-d0bf-4467-912f-a73715f7f813" />

Evolution du prix selon la disponibilité


<img width="592" height="447" alt="prix dispo" src="https://github.com/user-attachments/assets/94994ecb-7943-40af-9b21-99fa0a8a25bf" />


<img width="563" height="321" alt="prix dispo tbl" src="https://github.com/user-attachments/assets/be2842cf-ba75-4fcd-be3f-3c8cf54ff3ef" />


Evolution du prix selon le Lieu

<img width="783" height="467" alt="prix lieu" src="https://github.com/user-attachments/assets/5c4bfdea-d0c6-49a8-9756-9543e4f20583" />


<img width="547" height="427" alt="prix lieu tbl" src="https://github.com/user-attachments/assets/06ee2d46-8e35-49bf-8839-b5800aad512b" />



Evolution du prix par disponibilité et par Lieu

<img width="351" height="425" alt="prix dispo lieu tbl" src="https://github.com/user-attachments/assets/8ac8b3aa-af22-44a2-b9a6-a2b17c572aac" />


<img width="499" height="451" alt="prix dispo lieu" src="https://github.com/user-attachments/assets/b63a2b07-1832-4ce9-af96-020a254a5fde" />




#### Bon à savoir

1. Nous avons supprimé tous les zéros et les valeurs manquantes dans la colonnes des prix car cela aurait influencé grandement les résultats ,le faisant nous avons perdu une partie des données. Néanmoins ces résultats donne une vision d'ensemble.

2. Les prix sont en FCFA

3. Les produits sont vendus par Kg, donc le prix représente le prix du Kg.



















