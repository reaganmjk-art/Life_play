# LIFEPLAY — prototype fonctionnel

LIFEPLAY est un prototype mobile-first en français pour un projet étudiant. Il regroupe :
- My Life : tâches quotidiennes et objectif du jour.
- Food Life : stock alimentaire, dates limites et idées de repas.
- IT Play : quiz informatique, explications et points XP.
- Mood Play : journal d'humeur facultatif et idées de pauses.
- LIFEPLAY CORE : profil, niveaux, badges, statistiques, historique, export/import et réinitialisation.

## Lancer l'application
### Méthode la plus simple
Ouvrir `index.html` dans un navigateur récent. Les fonctions principales marchent localement. Certaines fonctions d'installation hors ligne (PWA) nécessitent un serveur local ou HTTPS.

### Serveur local recommandé
Si Python est installé, ouvrir un terminal dans ce dossier et lancer :
```bash
python -m http.server 8000
```
Puis ouvrir `http://localhost:8000` dans le navigateur.

Pour tester sur un téléphone, l'ordinateur et le téléphone doivent être sur le même réseau Wi-Fi et le serveur doit être accessible depuis le téléphone. Pour une vraie installation PWA, utiliser HTTPS sur un hébergement ou un environnement de test sécurisé.

## Données et limites
- Les données sont enregistrées dans le `localStorage` du navigateur, sur l'appareil.
- Il n'y a pas de compte en ligne, de synchronisation multi-appareils, de serveur ni de base de données distante.
- Le budget du prototype peut être nul avec des outils gratuits. Un domaine, un hébergement ou un développement professionnel peuvent coûter plus cher.
- Les idées de repas sont simples et ne remplacent pas un avis nutritionnel. Les rappels de dates sont des aides : vérifiez toujours l'état et l'étiquetage des aliments.
- Le suivi d'humeur est un outil de bien-être personnel, pas un diagnostic médical.

## Répartition possible de l'équipe
1. Food Life : données alimentaires, dates et idées de repas.
2. My Life : tâches, objectifs et habitudes.
3. IT Play : quiz et contenu pédagogique.
4. Mood Play : humeur, activités de pause et expérience utilisateur.
5. LIFEPLAY Core : intégration, tests, documentation et présentation.

Chaque membre devrait tester les fonctions des autres modules. Le prototype est une base de démonstration ; avant une diffusion publique, prévoyez des tests utilisateurs, une politique de confidentialité, des tests de sécurité et une vraie stratégie de sauvegarde.


## Installation sur un téléphone
Pour installer LIFEPLAY comme une PWA, les fichiers doivent être publiés sur une adresse HTTPS. Ouvrir simplement `index.html` depuis le stockage du téléphone ne suffit pas pour activer toutes les fonctions PWA. Le manifeste inclut des icônes 192×192 et 512×512.

Après publication sur HTTPS :
- **Android / Chrome** : ouvre l'adresse de LIFEPLAY, touche le menu ⋮ puis « Installer l'application » ou « Ajouter à l'écran d'accueil ».
- **iPhone / Safari** : ouvre l'adresse, touche Partager, puis « Sur l'écran d'accueil ».

Les libellés peuvent varier selon le navigateur et le téléphone.
