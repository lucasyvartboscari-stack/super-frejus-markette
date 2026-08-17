# Super Fréjus Markette 🛒

Application de liste de courses pensée pour Fréjus (Var), faite pour mes parents.

## Ce qu'elle fait

- **On tape un produit** (ex. « lait ») → l'appli propose les magasins de Fréjus qui l'ont en rayon, **du plus proche de la maison (quartier Tour de Mare) au plus loin**, avec leurs adresses.
- **On touche un magasin** → l'article rejoint sa liste. La liste de courses est **groupée par magasin** : « Lidl : papier toilette, essuie-tout, savon… ».
- Chaque produit a une **image** et un **prix indicatif moyen** (modifiable d'un geste) ; l'appli affiche un **sous-total par magasin** et le **total estimé**.
- Au magasin, on **coche** ce qu'on achète, puis « **Courses faites ✓** » enlève les articles cochés.
- Magasins intégrés : Auchan (ex-Géant), E.Leclerc Valescure, Intermarché, Casino, Lidl, Aldi ×2, Netto, Carrefour City/Express/Contact, Picard, Grand Frais, Ô Paysans (producteurs, Puget), et le marché du centre-ville. On peut en ajouter d'autres.

## Technique

- Une seule page HTML, **aucune dépendance** : ouvrez `index.html` dans un navigateur, c'est tout.
- Les données sont enregistrées **sur l'appareil** (localStorage) — pas de compte, pas de serveur.
- Sur Android : ouvrir la page dans Chrome → menu ⋮ → « Ajouter à l'écran d'accueil ».
- Thèmes clair et sombre automatiques.

## Limites connues

- Les prix sont des moyennes indicatives (France, 2026), pas les prix du jour de chaque enseigne.
- « En rayon » signifie que ce type de produit s'y vend habituellement — le stock en temps réel des magasins n'est pas public.
- La liste des magasins de Fréjus a été préparée en août 2026 : pensez à vérifier les horaires.
- Pas de synchronisation entre deux téléphones (chacun a sa liste).

---

Fait avec [Claude Code](https://claude.com/claude-code).
