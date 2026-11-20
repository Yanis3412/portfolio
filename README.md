# Portfolio · Yanis Achkar

Site statique (HTML, CSS, JavaScript), sans build ni dépendance. Français et anglais.

```
index.html                  Toute la page (styles, contenu FR/EN, script)
assets/CV_Yanis_Achkar.pdf  CV téléchargeable
assets/img/                 Photo et captures des projets
```

## Modifier le contenu

- Textes de la page : objet `T` dans le script (`fr` et `en`), et le HTML pour la version française affichée sans JavaScript.
- Projets : tableau `P` (titre, résumé, technologies, points détaillés, liens, captures).
- Compétences : tableau `SK`.
- Nouveau CV : remplacer `assets/CV_Yanis_Achkar.pdf` en gardant le même nom.

## Tester en local

Ouvrir `index.html` dans un navigateur, ou lancer `npx serve .` dans ce dossier.

## Mettre en ligne (Vercel, gratuit)

1. Créer un dépôt GitHub `portfolio` et y envoyer le contenu de ce dossier.
2. Sur vercel.com : *Add New → Project*, choisir le dépôt, laisser les réglages par défaut (Framework : *Other*), *Deploy*.
3. Optionnel : ajouter un nom de domaine dans *Settings → Domains*.

Alternative : GitHub Pages (*Settings → Pages → Deploy from a branch → main / root*).
