UFR Sciences et Techniques
TP – JavaScript

Auteur: Salmane Koraichi
Date: 2025-10-15

Résumé du TP
-----------
Ce dépôt contient un CV HTML/CSS enrichi avec du JavaScript pour le TP de l'UFR Sciences et Techniques.

Contenu ajouté / fonctionnalités réalisées
- Microdonnées Schema.org (Person) pour améliorer l'indexation et la sémantique.
- Responsive CSS via `css/responsive.css` (points d'arrêt 740px, 570px, 480px).
- Font Awesome (v4) et police Raleway (Adobe Edge) intégrées.
- Détails interactifs pour les expériences : boutons "Détails" qui affichent une description développée. Une seule description est affichée à la fois. L'apparition est animée (transition sur la hauteur).
- Tooltips pour les compétences : un tooltip suit le curseur et montre une brève description; comportement tactile adapté (tap pour afficher).
- Auto-évaluation : étoiles (★/☆) et histogramme pour évaluer vos compétences techniques (données dans le script JS).

Fichiers importants
- `ubo-resume.html` — page principale du CV (HTML, microdonnées, script JS embarqué).
- `css/resume.css` — styles principaux, styles pour détails, tooltips et autoévaluation.
- `css/responsive.css` — media queries pour rendre le CV responsive.

Comment tester localement
------------------------
1. Ouvrir `ubo-resume.html` dans un navigateur récent (Chrome/Firefox).
2. Tester les boutons "Détails" : ouvre/ferme les descriptions et n'affiche qu'une description à la fois.
3. Survoler une compétence : le tooltip doit suivre le curseur. Sur mobile, taper la compétence affiche le tooltip pendant quelques secondes.
4. Vérifier la section Auto-évaluation : les étoiles et l'histogramme s'affichent et les barres s'animent.
5. Redimensionner la fenêtre pour tester la réactivité (<=740px, <=570px, <=480px).

Déploiement sur GitLab
----------------------
1. Créer un nouveau dépôt GitLab.
2. Pousser les fichiers du dossier `MonCV` dans le dépôt.
3. Activer GitLab Pages (optionnel) ou servir le fichier HTML via un simple serveur web (ex: `python3 -m http.server`).

Remarques et améliorations possibles
- Remplacer Adobe Edge par Google Fonts (plus simple à maintenir).
- Migrer Font Awesome vers une version récente.
- Ajouter édition en ligne des notes d'auto-évaluation (enregistrer dans localStorage).
- Ajouter tests unitaires pour le JS.

Contact
-------
Salmane Koraichi — salmane.koraichi@gmail.com

Lien du TP déployé : https://salmanelebrestois.github.io/CV/ubo-resume.html
