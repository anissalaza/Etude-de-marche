###### _Ce projet a été réalisé dans le cadre de la formation Data Analyst (Bac +3/4, certifié RNCP) proposée par OpenClassrooms. Il fait partie des 9 projets à valider afin d'en être diplômé_.

# Etude-de-marche

## Introduction

Dans le cadre de ce projet, je devais réaliser une étude de marché pour une entreprise agro-alimentaire spécialisée dans le poulet.  L'objectif était de cibler plus particulièrement certains pays, dans le but d'approfondir ensuite l'étude de marché. Plus particulièrement, l'idéal était de produire des "groupes" de pays, plus ou moins gros, dont on connaît les caractéristiques. Ces groupes ont été projetés sur une carte du monde, pour faciliter la lecture et la compréhension.

Ce projet nous a permis de manipuler des données en _Python_, et d'appliquer des **statistiques descriptives**, mais aussi **inférentielles**, ainsi que des **classifications automatiques**. De plus, des analyses en composantes principales (ACP) ont été réalisées.

* Outils utilisés :
  * Jupyter et JupyterLab
  * Les librairies Python : Pandas, Numpy, Matplotlib, Seaborn, Scipy, Sklearn, Geopandas, Json et Bokeh 
  * PowerPoint
Le script pourra ainsi être ouvert grâce à Jupyter ou JupyterLab, au choix. 

Le projet intitulé "_Etude de marché_" est composé d'un script contenant l'[étude de marché](https://github.com/anissalaza/Etude-de-marche/blob/main/Etude%20de%20marche.ipynb). Des [dendrogrammes](https://github.com/anissalaza/Etude-de-marche/tree/main/Dendrogrammes) ainsi que des fichiers csv : le [premier](https://github.com/anissalaza/Etude-de-marche/tree/main/Listes%20des%20pays) contient la liste des pays ainsi que (pour chacun d'entre eux) leur groupe qui a été déterminé après avoir découpé le dendrogramme, et le [second](https://github.com/anissalaza/Etude-de-marche/tree/main/Centroides%20des%20pays), lui, contient les centroïdes des groupes et leurs coordonnées dans chacune des dimensions. Pour plus de compréhension, des [cartes du monde](https://github.com/anissalaza/Etude-de-marche/tree/main/Cartes) affichant les différents groupes (clusters) ont été produites. Les résultats ont été présentés lors d'une [soutenance](https://github.com/anissalaza/Etude-de-marche/blob/main/Soutenance.pdf) évaluée par un examinateur.

------------------------------------------------

## Organisation du repository

#### *Etude de marché*
Ce fichier contient le **notebook Jupyter** permettant d'effectuer l'étude de marché.

#### *Listes des pays*
Ce dossier contient les fichiers produits lors de l'étude de marché, à savoir les listes des pays éparpillés dans des groupes (clusters).

#### *Centroïdes des pays*
Ce dossier contient les fichiers produits lors de l'étude de marché, à savoir les centroides des groupes et leurs coordonnées.

#### *Cartes*
Ce dossier contient les représentations graphiques (cartes du monde) des clusters déterminés. 

#### *Dendrogrammes*
Ce dossier contient tous les dendrogrammes générés lors de l'analyse des données.

#### *Soutenance*
Ce fichier a été présenté lors de la **soutenance** validant le projet.

