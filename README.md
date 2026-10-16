# ETS MBOG FOOD INDUSTRY — Site vitrine

Site statique en français, style luxe africain vert forêt et or. Prévu pour un hébergement statique gratuit et un nom de domaine personnalisé si le fournisseur permet de relier un domaine externe.

## Fichiers
- `index.html` : site public (accueil, présentation, catalogue, personnalisation, contact)
- `styles.css` : design responsive
- `script.js` : navigation mobile, recherche catalogue et liens WhatsApp
- `assets/logo-officiel-a-remplacer.svg` : logo provisoire à remplacer par le logo officiel
- `assets/favicon.svg` : favicon
- `admin/index.html` : outil local de préparation de fiches produits
- `assets/README-ASSETS.txt` : instructions détaillées pour les photos et le logo

## Fonctionnalités incluses
- Catalogue de trois catégories éditoriales avec recherche.
- Boutons de demande de détails/devis ouvrant WhatsApp.
- Formulaire de contact qui prépare un message WhatsApp, sans backend.
- Page `admin/` qui génère une fiche produit JSON téléchargeable.
- Mise en page adaptée au mobile et à l'ordinateur.

## Limite importante de l'administration
La page `admin/` est un outil statique non protégé. Elle ne publie pas les produits sur le site, ne sauvegarde pas de données sur un serveur et ne doit pas être considérée comme un tableau de bord sécurisé. Un vrai espace d'administration nécessite une authentification, une base de données ou un CMS, un stockage d'images et des règles d'accès.

## Tester
Décompressez l'archive et ouvrez `index.html` dans un navigateur. Pour vérifier correctement tous les liens, déployez le dossier sur un hébergement ou utilisez un serveur local statique.

## Publication sur hébergement gratuit
1. Créez un compte chez un hébergeur statique gratuit (par exemple GitHub Pages, Netlify ou Cloudflare Pages, selon les conditions en vigueur).
2. Téléversez le contenu du dossier du site ou reliez un dépôt Git.
3. Configurez le dossier de publication à la racine du site (ce dossier contient `index.html`).
4. Testez la page d'accueil, les liens WhatsApp et la recherche catalogue.
5. Pour utiliser un domaine personnalisé, achetez/réservez un domaine puis configurez les DNS dans le panneau de l'hébergeur. L'hébergement peut être gratuit, mais le domaine est généralement payant.
6. Activez/contrôlez HTTPS.

## Remplacements indispensables avant publication
### Logo officiel
Remplacez `assets/logo-officiel-a-remplacer.svg` par le vrai logo de MBOG FOOD INDUSTRY. Le plus simple est de garder le même nom de fichier et de fournir un fichier SVG ou PNG compatible. Si vous utilisez un autre nom, modifiez les deux références dans `index.html`. Le favicon peut aussi être remplacé.

### Photos officielles des produits
Les illustrations de bouteilles sont dessinées en CSS, pas des photos des produits réels. Ajoutez les photos officielles dans `assets/` (ex. `vin-fruit-rouge.jpg`, `bouteille-personnalisee.jpg`) et remplacez les blocs `.product-image` dans `index.html` par des éléments `<img>` avec un texte alternatif. Mettez aussi à jour les styles dans `styles.css`. Utilisez seulement des photos dont l'entreprise possède les droits.

### Informations commerciales et légales
Confirmez les produits exacts, prix, volumes, ingrédients, disponibilité, quantités minimales, délais, livraisons, conditions de commande et toutes les mentions légales applicables. Les prix ne sont volontairement pas inventés.
Confirmez l'e-mail et les deux numéros de téléphone.
Le numéro WhatsApp configuré est `+237 655 143 778`; modifiez `237655143778` dans `index.html`, `script.js` et `admin/index.html` si nécessaire.

## Contact
- Yaoundé, Cameroun
- 655 143 778 / 690 908 807
- Mbogfoodi@gmail.com
- Slogan : « Le savoir d'un peuple dans une bouteille »
