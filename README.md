## Project-Easter-2023

- Edgar DORIGNAC
- Julien GANDIN
- Kyllian MOSNAT

Ce projet est destiné à apprendre à utiliser Git de manière efficace en travaillant sur un projet fictif.

## Étapes
### Step 1 : Initialisation et configuration du projet

    1. Initialisez le dépôt Git.
    2. Chaque coéquipier doit cloner le dépôt en local.
    3. Créez la branche develop et poussez-la sur le dépôt distant.

### Step 2 : Créer la page Happy Easter en français

    1. Créez une nouvelle branche à partir de develop appelée feature/french_happy_easter.
    2. Ajoutez la page Happy Easter en français et un lien vers cette page depuis la landing page.
    3. Ajoutez et commitez les modifications.
    4. Poussez la branche feature/french_happy_easter sur le dépôt distant.
    5. Fusionnez la branche feature/french_happy_easter avec develop sur GitHub.

### Step 3 : Créer les pages Happy Easter en anglais, espagnol et italien

    1. Pour chaque langue, créez une nouvelle branche à partir de develop appelée feature/<langue>_happy_easter.
    2. Ajoutez la page Happy Easter dans la langue correspondante et un lien vers cette page depuis la landing page.
    3. Ajoutez et commitez les modifications.
    4. Poussez la branche feature/<langue> sur le dépôt distant.
    5. Fusionnez chaque branche feature/<langue> avec develop sur GitHub.
    6. Pour créer une release en production, fusionnez develop avec main et créez un tag Git (v1.0.0).

    La création de ce tag Git va nous permettre de savoir quelle version est actuellement en production.
    Ils permettent de marquer des points spécifiques dans l'historique des commits, pour indiquer une version particulière ou une release.

### Step 4 : Créer les pages Happy Easter en portugais, allemand et polonais

  Répétez les étapes de la Step 3 pour chaque langue, sans créer de release pour le moment.

### Step 5 : Remplacer la page italienne par une page russe (hotfix)

    1. Créez une nouvelle branche à partir de main appelée hotfix.
    2. Remplacez la page italienne par une page russe et mettez à jour le lien sur la landing page.
    3. Ajoutez et commitez les modifications.
    4. Poussez la branche hotfix sur le dépôt distant.
    5. Fusionnez la branche hotfix avec main sur GitHub. 
      (On pense qu'il aurait dû également fusionner la branche avec develop pour éviter les conflits à la fin)
    6. Créez un nouveau tag Git pour la release de production incluant le hotfix (v1.0.1).

### Step 6 : Créer la page Happy Easter en hollandais

  Suivez les étapes de la Step 3 pour la langue hollandaise, sans créer de release pour le moment.

### Step 7 : Ajouter la page Happy Easter en serbe

    1. Suivez les étapes de la Step 3 pour la langue serbe.
    2. Créez une release en production en fusionnant develop avec main et en créant un nouveau tag Git (v1.1.0).

### Step 8 : Préparer une release pour la production avec la page en hollandais

    1. Fusionnez les changements de la branche develop dans la branche main. 
    2. Créez une nouvelle release pour la production incluant la page Happy Easter en hollandais. (v1.2.0)
