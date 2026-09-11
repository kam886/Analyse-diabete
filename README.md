# Analyse du diabète en France

## Présentation du projet

Ce projet analyse l’évolution du diabète en France entre **2015 et 2024** à partir des données publiques de l’Assurance Maladie.

L’objectif est de transformer des données de santé publique en indicateurs compréhensibles afin de :

- suivre l’évolution du nombre de personnes prises en charge ;
- comparer la prévalence selon l’âge et le sexe ;
- identifier les territoires présentant les prévalences les plus élevées ;
- analyser les dépenses remboursées attribuées au diabète ;
- présenter les principales comorbidités associées.

## Problématique

**Comment les données de l’Assurance Maladie peuvent-elles aider à repérer les populations et les territoires nécessitant une attention renforcée en matière de prévention du diabète ?**

## Sources des données

Les données proviennent du portail public **Data pathologies de l’Assurance Maladie** :

- [Présentation des données sur les pathologies](https://data.ameli.fr/pages/pathologies/)
- [Effectifs et prévalence](https://data.ameli.fr/explore/dataset/effectifs/)
- [Dépenses remboursées](https://data.ameli.fr/explore/dataset/depenses/)
- [Comorbidités](https://data.ameli.fr/explore/dataset/comorbidites/)

**Période étudiée : 2015–2024.**

## Préparation et fiabilisation des données

Les données publiques étaient déjà relativement structurées. Le travail de préparation a principalement consisté à :

- sélectionner les observations relatives au diabète ;
- conserver les niveaux d’agrégation utiles à l’étude ;
- traiter les valeurs vides ;
- convertir les indicateurs dans des formats numériques exploitables ;
- harmoniser les codes des départements et des régions ;
- associer les codes géographiques à leurs libellés ;
- séparer les données nationales, territoriales, démographiques et financières ainsi que les données sur les comorbidités ;
- contrôler les agrégations afin d’éviter les doubles comptages entre les hommes, les femmes et l’ensemble de la population ;
- vérifier la cohérence des effectifs, des populations, des prévalences et des dépenses.

La préparation initiale a été réalisée avant l’importation dans Excel. Les calculs, les contrôles complémentaires, les filtres et les visualisations ont ensuite été intégrés dans le classeur.

## Tableau de bord

Le fichier Excel contient :

- des filtres interactifs par **année** et par **sexe** ;
- quatre indicateurs principaux :
  - le nombre de patients pris en charge ;
  - la prévalence nationale ;
  - les dépenses remboursées ;
  - la dépense moyenne par patient ;
- un graphique d’évolution nationale ;
- un profil de prévalence par classe d’âge ;
- un classement des départements ;
- un classement des régions ;
- des légendes dynamiques indiquant les filtres sélectionnés ;
- des tableaux synthétiques présentant uniquement les résultats essentiels.

Les feuilles détaillées permettent également de consulter les données nationales, départementales, les dépenses, les classes d’âge et les comorbidités.

![Aperçu du tableau de bord](assets/dashboard_diabete.png)

## Principaux résultats

- En 2024, environ **4,47 millions de personnes** sont prises en charge pour diabète, contre **3,59 millions en 2015**.
- La prévalence nationale atteint environ **6,6 % en 2024**.
- Les classes d’âge comprises entre **75 et 84 ans** présentent les niveaux de prévalence les plus élevés.
- Les dépenses remboursées attribuées au diabète atteignent environ **11,5 milliards d’euros en 2024**.
- La dépense moyenne représente environ **2 572 euros par patient en 2024**.
- Les écarts territoriaux montrent l’intérêt de cibler les analyses et les actions de prévention selon les territoires.

## Limites de l’étude

- Les prévalences territoriales présentées ne sont pas standardisées sur l’âge.
- La structure démographique peut expliquer une partie des différences entre les territoires.
- Le champ étudié correspond aux personnes prises en charge selon la méthodologie de l’Assurance Maladie.

## Compétences mobilisées

- Préparation et fiabilisation des données
- Contrôle de cohérence
- Analyse descriptive
- Construction d’indicateurs de santé
- Formules Excel et fonctions conditionnelles
- Création de filtres et de graphiques interactifs
- Data visualisation
- Restitution de résultats pour l’aide à la décision


## Licence

Ce projet est distribué sous licence [MIT](LICENSE).

Les données utilisées restent soumises aux conditions de réutilisation de l’Assurance Maladie.

