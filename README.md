# Trame du dépôt du projet article
Lorsque nécessaire, des informations pourrront être communiquées sur https://prodageo.github.io/depot-article/.

## Organisation du référentiel de livraison
![](https://i.imgur.com/OrzkLUN.png)
- 0.SUIVI : répertoire pour les fichiers de la gestion de projets
  - cr_reunion_avancement : contient autant de répertoire que de réunions d'avancement (une par semaine)
    - aaaammjj : le répertoire a pour nom la date à laquelle a eu lieu la réunion d'avancement
      - cr.md : contient la liste des tâches dont la date (non vide) a été modifié et la justification de cette modification
      - liste_nouvelles_taches.htmlm : voir la diapo 14 du support _reunion_avancement.pdf_
      - liste_taches_en_retard.html : voir la diapo 13 du support _reunion_avancement.pdf_
- 1.INIT : répertoire pour les fichiers d'initialisation et de lancement du projet
  - note_de_cadrage.md : la note de cadrage avec l'ensemble des caractéristiques du projet. A noter que le macro-planning est vide (il est à consulter sur Jira, menu _Feuille de route_)
- 2.ANA : répertoire pour les fichiers d'analyse (analyse de la situation, contact avec le réel)
  - questionnaire.md : liste des interlocuteurs retenus pour l'entretien et questions qui leur sont adressées
    - autres formats :
      - questionnaire.csv
      - questionnaire.xlsx : format à utiliser exclusivement sur la station de travail, sauvegarder systématiquement des copies au format csv sur Github
