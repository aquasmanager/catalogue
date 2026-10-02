# Dépôt public du catalogue (à créer sur GitHub)

Contenu à placer dans le dépôt public du catalogue (ex. `aquasmanager/catalogue`) :
`.github/ISSUE_TEMPLATE/espece.yml` = formulaire « Proposer une espèce ».

- Les propositions envoyées depuis l'appli arrivent comme issues via le hub
  (jeton du hub, étiquettes `espèce` et `proposition` à créer dans le dépôt).
- Les utilisateurs ayant un compte GitHub peuvent aussi ouvrir le formulaire
  prérempli depuis l'appli (lien configuré par `AQUAS_CATALOG_ISSUES_URL`).
- Une espèce acceptée est ajoutée au catalogue livré avec l'appli
  (`AquasManagerApi/services/species_catalog.py`), puis l'issue est fermée.
