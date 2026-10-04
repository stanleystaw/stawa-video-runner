# STAWA Video Runner

Runner public du pipeline vidéo **STANGENX**.

Ce dépôt ne contient **aucun code métier** : il héberge uniquement le workflow
GitHub Actions qui exécute le traitement vidéo sur des machines gratuites
(Actions illimitées pour les dépôts publics).

- 🔒 L'algorithme de traitement reste dans un dépôt **privé** (récupéré au
  runtime via jeton chiffré).
- 🔒 Les vidéos traitées sont stockées dans une Release **privée**.
- 🔒 Aucune donnée de tâche n'apparaît dans les logs (masquage systématique).

Déclenchement : `repository_dispatch` uniquement (accès en écriture requis).
