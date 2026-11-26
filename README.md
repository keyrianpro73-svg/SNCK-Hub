# SNCK Hub (fichier unique)
1. Créer un dépôt GitHub vide.
2. Envoyer à la racine tout le contenu du ZIP (index.html, netlify.toml, package.json, netlify/).
3. Sur Netlify : « Add new site » → « Import from Git », choisir le dépôt (aucun build requis).
4. Vérifier le déploiement : `https://VOTRE-SITE.netlify.app/api/db?id=test12345` doit répondre 404 JSON (fonction active).
5. Ouvrir le hub, cliquer sur l'icône nuage, « Créer un nouveau code », puis partager le lien affiché.
