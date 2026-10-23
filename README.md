# RAF · Check ménage — Stade Paul-Lignon

Application web mobile (une seule page, sans serveur) pour contrôler le ménage des espaces hospitalités R+1
(tribunes Ouest/Haras et Est/Cathédrale) à chaque match à domicile du Rodez Aveyron Football.

- 17 matchs à domicile Ligue 2 2026-2027, passages « Veille » et « Après match »
- 58 espaces issus du cahier des charges, par catégorie, avec récurrence (match / mois / trimestre)
- Signalement de problème (commentaire + photos) et rapport PDF
- Données stockées localement sur l'appareil (localStorage)

## Publier avec GitHub Pages
1. Déposer ces fichiers à la racine du dépôt.
2. Settings → Pages → Branch `main` / dossier `/ (root)` → Save.
3. Ouvrir l'URL sur le téléphone puis « Ajouter à l'écran d'accueil ».

Le PDF utilise jsPDF (cdnjs). Calendrier : dates susceptibles d'évoluer, à modifier dans le tableau `M` de `index.html`.
