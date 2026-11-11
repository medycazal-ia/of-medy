# MAD_optimise — page de présentation du dossier

Adresse visée : https://medy.site/MAD_optimise/

## Dépôt chez LWS (cPanel)
1. cPanel > Gestionnaire de fichiers > `public_html` du domaine medy.site.
2. « Charger » le fichier `MAD_optimise.zip`, puis clic droit > « Extraire » dans `public_html`.
3. Vérifier que le dossier `public_html/MAD_optimise/` contient `index.html` et `assets/`
   (nom exact, majuscules comprises).
4. Ouvrir https://medy.site/MAD_optimise/ en fenêtre privée.

## Protection recommandée (la page décrit la situation d'un proche)
cPanel > Sécurité > « Confidentialité du répertoire » (protection par mot de passe) > dossier
`MAD_optimise`. La page contient déjà `noindex` (pas de référencement Google), mais l'adresse
reste lisible par quiconque la connaît.

## Si medy.site est servi par Render (dépôt medy-site-backend)
Copier ce dossier dans `public-site/MAD_optimise/` du dépôt puis déployer : le serveur Express
sert `public-site/` en statique.
