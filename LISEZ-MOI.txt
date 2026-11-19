DISPENSES EPS : VERSION HORS CONNEXION POUR IPAD
=================================================

Ce dossier contient l'application. Elle doit être mise en ligne UNE FOIS
(gratuitement, sur GitHub Pages) pour pouvoir être installée sur l'iPad.
Ensuite, elle fonctionne sans connexion.

Seul le code est mis en ligne. Les données de tes élèves restent dans l'iPad.


1. METTRE EN LIGNE (une seule fois)
-----------------------------------
a. Crée un compte gratuit sur https://github.com
b. Bouton « + » en haut à droite > New repository.
   Nom : dispenses-eps   ·   Public   ·   Create repository
c. Sur la page du dépôt, clique sur « uploading an existing file ».
   Sélectionne ces 6 fichiers (pas le dossier) :
     index.html, sw.js, manifest.webmanifest,
     icon-192.png, icon-512.png, apple-touch-icon.png
   puis « Commit changes ».
d. Settings > Pages > Source : « Deploy from a branch »
   Branch : main   /(root)   > Save
e. Attends 1 à 2 minutes. L'adresse s'affiche en haut de la page Pages :
     https://TON-IDENTIFIANT.github.io/dispenses-eps/


2. INSTALLER SUR L'IPAD
-----------------------
a. Ouvre cette adresse dans Safari.
b. Bouton Partager > « Sur l'écran d'accueil » > Ajouter.
c. Ouvre l'application depuis l'écran d'accueil UNE PREMIÈRE FOIS
   AVEC LA CONNEXION, quelques secondes.
d. C'est prêt : elle s'ouvre maintenant sans réseau.
   (Réglages & données > « Hors connexion : prêt » le confirme.)

Saisis tes élèves dans l'application de l'écran d'accueil, pas dans
Safari : les deux ne partagent pas leurs données.


3. SAUVEGARDES
--------------
Réglages & données > « Enregistrer une sauvegarde » > Enregistrer dans
Fichiers (iCloud Drive de préférence). Si l'application est supprimée de
l'écran d'accueil, ses données le sont aussi : garde une copie récente.
Pour tout récupérer : « Restaurer une sauvegarde ».


4. METTRE À JOUR L'APPLICATION
------------------------------
Remplace index.html sur GitHub par la nouvelle version, et augmente le
numéro dans la première ligne de sw.js (dispenses-eps-v1 > v2).
L'iPad récupère la mise à jour à la prochaine ouverture avec connexion.
Tes données ne sont pas touchées.
