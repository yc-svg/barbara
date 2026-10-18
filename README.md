# Mangia Vicino

Page mobile qui liste les meilleures adresses de Naples et Rome (pizzerias, trattorias, street food, douceurs, cafés), triées par distance depuis votre position GPS, avec liens Google Maps et Plans.

Site statique : un seul fichier `index.html`, aucune clé API.

## Déployer sur Vercel

1. Sur vercel.com, "Add New" puis "Project", importer ce dépôt.
2. Framework : "Other", aucune commande de build. Cliquer sur "Deploy".
3. Ouvrir l'adresse en `https://...vercel.app` dans Safari sur iPhone, autoriser la localisation, puis "Partager" et "Sur l'écran d'accueil".

## Modifier les adresses

Les adresses sont dans le tableau `SPOTS` de `index.html` (nom, adresse, coordonnées, catégorie, prix, description, conseil).
