# Site vitrine FoldersPanel — illanor-solutions.fr

Contenu de ce dossier : `index.html` (page bilingue FR/EN, bascule automatique selon la langue du navigateur),
`politique-confidentialite.html`, `img\` (logo, captures, `demo.gif`), `CNAME` (nom de domaine pour GitHub Pages).
Tout est statique : aucun serveur, aucun script côté serveur.

## Mise en ligne gratuite (GitHub Pages)

Compte GitHub : `illanor-solutions`.

1. **New repository** nommé exactement `illanor-solutions.github.io`, Public, créer. Ce nom fait de lui le site racine
   du compte : `https://illanor-solutions.github.io/`, sans sous-dossier.
2. **Add file › Upload files** : glisser tout le contenu de ce dossier `Site` (fichiers et dossier `img`), Commit.
   GitHub Pages s'active tout seul pour un dépôt de ce nom ; la page est en ligne en 1–2 min.
3. **Domaine** : Settings › Pages › *Custom domain* doit afficher `illanor-solutions.fr` (le fichier `CNAME` le fait).
   Chez IONOS › Domaines › DNS de illanor-solutions.fr :
   - 4 enregistrements **A** pour `@` : `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - 1 enregistrement **CNAME** pour `www` : `illanor-solutions.github.io`
   - supprimer les enregistrements A/AAAA par défaut d'IONOS sur `@` (page de parking).
   Quand Settings › Pages affiche « DNS check successful » (minutes à quelques heures), cocher **Enforce HTTPS**.
4. Mettre à jour : remplacer les fichiers dans le dépôt (Upload files), la page se met à jour seule.

## Remplacer les captures

Les images de `img\` viennent des captures envoyées pendant le développement (panneau au survol, paramètres).
Pour une version finale : capture du panneau latéral (accueil), du survol, d'un dossier ouvert avec la recherche,
puis refaire `demo.gif` (diaporama de 3–4 vues, 800 px de large).

## Liens utiles

- Fiche Store : `https://apps.microsoft.com/detail/9P9MSB472G3Z` (le bouton de la page y mène, `?mode=direct`).
- Badge officiel : `https://get.microsoft.com/images/fr-fr%20dark.svg` (la page affiche un bouton de secours s'il ne se charge pas).
- Mettre l'adresse du site dans Partner Center › Propriétés › Support info › Site Web.
