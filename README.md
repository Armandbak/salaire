# Filtre_salaire
1. Créer un nouveau dépôt sur GitHub :
   - Je me connecte à mon compte GitHub.
   - Je clique sur le signe plus en haut à droite, puis je sélectionne "New repository".
   - Je donne un nom à mon dépôt, une description (optionnelle) et configure éventuellement d'autres paramètres. Puis je clique sur "Create repository".

2. Initialiser un dépôt Git local :
   - J'ouvre un terminal.
   - J'accède au répertoire racine de mon projet en utilisant la commande cd.
   - J'initialise un dépôt Git en utilisant la commande git init pour suivre les changements de mon projet.

3. Ajouter les fichiers au dépôt Git :
   - J'utilise la commande git add pour ajouter les fichiers à l'index Git. Par exemple, git add . pour ajouter tous les fichiers.
   - J'utilise la commande git commit -m "Message de commit" pour valider les changements avec un message descriptif.

4. Configurer le dépôt distant :
   - Sur ma page de dépôt sur GitHub, dans la section "Quick setup", je m'assure de choisir "HTTPS" ou "SSH" selon la façon dont je souhaite me connecter.
   - Je note ou copie l'URL du dépôt.

5. Ajouter le dépôt distant :
   - J'utilise la commande git remote add origin <URL_du_dépôt> pour ajouter le dépôt distant. Par exemple, git remote add origin https://github.com/votre_utilisateur/votre_dépôt.git.

6. Pousser les modifications vers GitHub :
   - J'utilise la commande git push -u origin nom_de_votre_branche pour pousser mes modifications vers le dépôt distant sur GitHub.

Après avoir effectué ces étapes, mes fichiers seront importés de ma machine vers GitHub. Je pourrai désormais gérer mon code à distance sur GitHub et collaborer avec d'autres contributeurs si nécessaire.
