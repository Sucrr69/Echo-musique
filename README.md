# Écho Musique

Lecteur de musique installable (PWA), qui marche hors ligne. Tes musiques restent sur ton téléphone : elles ne sont jamais envoyées sur GitHub.

## Mise en ligne depuis un téléphone Android (environ 5 minutes)

1. Dans Chrome, va sur **github.com** et connecte-toi (ou crée un compte gratuit).
2. Touche **+** en haut, puis **New repository**.
   - Nom : `echo-musique`
   - Visibilité : **Public** (obligatoire pour GitHub Pages gratuit)
   - Touche **Create repository**.
3. Sur la page du dépôt, touche le lien **uploading an existing file**.
   Sélectionne les 5 fichiers d'un coup : `index.html`, `manifest.webmanifest`, `sw.js`, `icon-192.png`, `icon-512.png`.
   Touche **Commit changes**.
4. Va dans **Settings** (menu « ··· » sur mobile), puis **Pages**.
   - Source : **Deploy from a branch**
   - Branche : **main**, dossier **/ (root)**, puis **Save**.
5. Attends 1 à 2 minutes. Ton appli est en ligne à l'adresse :
   `https://TON-PSEUDO.github.io/echo-musique/`

## Installer l'appli

Ouvre l'adresse dans Chrome, puis :
- touche le bouton **Installer l'appli** sur l'accueil,
- ou menu **⋮**, puis **Installer l'application** (ou **Ajouter à l'écran d'accueil**).

L'icône Écho apparaît avec tes autres applis. Elle s'ouvre en plein écran et marche sans connexion après la première ouverture.

## Ajouter tes musiques

Onglet **Ma musique**, puis **Ajouter des fichiers**. Choisis tes MP3 / M4A / FLAC (Téléchargements, carte SD, Google Drive…).
Nomme tes fichiers `Artiste - Titre.mp3` pour un affichage propre.

## Mettre à jour l'appli plus tard

Remplace `index.html` dans le dépôt (Add file, puis Upload files). L'appli installée prend la nouvelle version à la prochaine ouverture avec connexion. Tes musiques et tes favoris sont conservés.

## À savoir

- Le dépôt est public : n'importe qui peut voir le code, mais pas ta musique.
- Si tu désinstalles l'appli ou effaces les données de Chrome pour ce site, les musiques importées sont supprimées de l'appli (les fichiers d'origine restent sur ton téléphone).
