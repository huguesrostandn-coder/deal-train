REMPLACEMENT DES VISUELS OFFICIELS

1. LOGO
- Ce site utilise provisoirement `assets/logo-officiel-a-remplacer.svg`.
- Remplacez ce fichier par le logo officiel de MBOG FOOD INDUSTRY.
- Conservez le même nom pour éviter de modifier le code.
- Si le logo est un PNG, nommez-le par exemple `logo-officiel-a-remplacer.png`, puis modifiez les deux références à ce fichier dans `index.html` et le chemin dans la page admin si vous l'ajoutez plus tard.
- Remplacez également `favicon.svg` si vous disposez d'un favicon officiel.

2. PHOTOS PRODUITS
- Les bouteilles visibles sur la page d'accueil et dans le catalogue sont des illustrations décoratives réalisées en CSS ; elles ne montrent pas vos produits réels.
- Préparez des photos nettes et autorisées de chaque produit, idéalement avec un arrière-plan cohérent et un éclairage de qualité.
- Placez-les dans ce dossier `assets/`, par exemple :
  * `vins-de-fruits.jpg`
  * `edition-evenementielle.jpg`
  * `bouteille-personnalisee.jpg`
- Dans `index.html`, remplacez les blocs `<div class="product-image ...">...</div>` par des images du type :
  `<img class="product-photo" src="assets/vins-de-fruits.jpg" alt="Bouteille de vin de fruits MBOG FOOD INDUSTRY">`
- Ajoutez dans `styles.css` :
  `.product-photo{width:100%;height:245px;object-fit:cover;display:block}`
- Les illustrations de la grande bannière et de la section personnalisation peuvent aussi être remplacées par des photos officielles.

3. À VÉRIFIER AVANT PUBLICATION
- Exactitude des noms et descriptions des produits.
- Prix, formats, disponibilités, modalités de commande et délais.
- Autorisations d'utilisation des photos.
- Coordonnées et informations légales de l'entreprise.
