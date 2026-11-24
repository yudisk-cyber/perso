# Atelier Perso 3D

Créateur de personnages 3D (PWA) qui s'appuie sur les données libres de MakeHuman.

## 1. Mettre l'appli en ligne (GitHub Pages)
1. Crée un dépôt, par exemple `atelier-perso`.
2. Envoie `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png` à la racine.
3. Settings → Pages → branche `main`, dossier `/ (root)`.

## 2. Charger les données (sur le PC, une seule fois)
1. Télécharge l'extension **MPFB** sur extensions.blender.org (bouton Download, .zip ~43 Mo).
2. Télécharge le pack **MakeHuman system assets** (page « Asset packs » de makehumancommunity.org).
   Optionnel : packs de cheveux, de peaux, de cils/sourcils supplémentaires.
3. Ouvre l'appli et donne-lui ces .zip (bouton ou glisser-déposer). Les données restent dans le navigateur.

## 3. Avoir les données sur le téléphone
Onglet Fichier → « Exporter le pack » → mets `pack.atperso` à côté de `index.html` dans le dépôt.
Le téléphone le charge tout seul au premier lancement.
Attention : GitHub refuse les fichiers de plus de 100 Mo.

## Licences
Les personnages créés sont libres (CC0). Les données de MakeHuman / MPFB gardent leur licence
(AGPL / GPL pour le code et les formes de base, CC0 pour les system assets) : si tu publies le pack,
garde le dépôt public et cite MakeHuman.

## Note
Les personnages sont toujours adultes : l'âge démarre à 20 ans.
