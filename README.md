# Lecture PI-RADS v2.1 — CIM El Amane

Aide à la lecture de l'IRM prostatique selon **PI-RADS v2.1** (ACR / ESUR /
AdMeTech, 2019), avec PI-QUAL v2 pour la qualité, PRECISE v2 pour la
surveillance active, PI-RR pour les récidives et une échelle de Likert après
HIFU.

Dr Djamel Benchiheub — Centre d'Imagerie Médicale El Amane, Constantine.

## Ce que c'est

Une **page HTML autonome**. Pas de serveur, pas de base de données, pas de
construction : `index.html` contient tout, y compris les images. Elle
fonctionne hors ligne une fois chargée.

## Aucune donnée patient

L'application ne demande ni nom, ni date de naissance, ni numéro de dossier,
et n'écrit rien dans le navigateur — pas de `localStorage`, pas de cookie,
aucun envoi réseau. **Tout disparaît à la fermeture de l'onglet.** Le
rattachement au patient se fait dans le dossier, pas ici.

L'export d'examen produit un fichier JSON que vous enregistrez vous-même ;
il ne contient que des données radiologiques.

## Mise à jour

Remplacez `index.html` par la nouvelle version et validez. GitHub Pages
republie en une minute environ.

## Référencement

`robots.txt` demande aux moteurs de ne pas indexer la page, et `index.html`
porte une balise `noindex`. Retirez les deux si vous voulez qu'elle soit
trouvable.

## Périmètre

Outil d'aide à la structuration de la lecture, destiné aux radiologues. Il ne
formule **aucune recommandation de prise en charge** et ne remplace pas le
jugement clinique.
