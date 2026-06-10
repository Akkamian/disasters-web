# Backlog du projet "Optimisation Sante+"

## USER STORIES

---

### Story 1 : Chargement initial plus rapide

**En tant que** nouvel utilisateur web,  
**je veux** que l’écran d’accueil charge en moins de 1,5 s  
**afin de** ne pas décrocher lors d’un pic de réseau lent.

- 🎯 Objectif : temps de chargement < 1500 ms
- 🧱 BP associée : réduire taille des ressources / lazy-loading
- 🛠️ KPI : LCP sur web (Lighthouse)
- 📅 Tag roadmap : M2

---

### Story 2 : Réduction poids images

**En tant que** utilisateur récurrent,  
**je veux** que les visuels du dashboard soient plus légers  
**afin de** économiser de la data sur mon forfait.

- 🎯 Objectif : 80% des images converties en WebP
- 🧱 BP associée : compression d’images / formats modernes
- 🛠️ KPI : poids total dossier `/assets` < 2 Mo
- 📅 Tag roadmap : M3

---

### Story 3 : Accessibilité améliorée

**En tant que** utilisateur malvoyant,  
**je veux** que les contrastes texte/fond soient conformes AA  
**afin de** pouvoir utiliser l’app sans difficulté visuelle.

- 🎯 Objectif : conformité AA WCAG
- 🧱 BP associée : respect contrastes (RGESN 6.3)
- 🛠️ KPI : score accessibilité Lighthouse > 90
- 📅 Tag roadmap : M4

...

---

### Story 4 : Réduction du nombre de requêtes réseau

**En tant que** utilisateur mobile,  
**je veux que** l'application effectue moins de requêtes réseau lors du chargement  
**afin de** réduire ma consommation de données et accélérer l'affichage.  

- 🎯 Objectif : passer de 1467 à moins de 40 requêtes
- 🧱 BP associée : mutualisation des ressources / suppression des appels inutiles
- 🛠️ KPI : nombre de requêtes Lighthouse < 40

--- 

### Story 5 : Compression des ressources statiques

**En tant que** utilisateur connecté avec un débit limité,  
**je veux** que les fichiers JavaScript, CSS et JSON soient compressés avant transfert  
**afin de** réduire le volume de données téléchargées.  

- 🎯 Objectif : activer Brotli ou Gzip sur 100 % des ressources statiques
- 🧱 BP associée : compression des ressources
- 🛠️ KPI : taille totale transférée < 5 Mo


### Story 6 : Réduction du JavaScript exécuté

**En tant que** utilisateur du site,  
**je veux** que seul le JavaScript nécessaire soit chargé et exécuté  
**afin de** réduire le temps d'attente avant interaction.  

- 🎯 Objectif : diminuer le TBT sous 200 ms
- 🧱 BP associée : suppression du code inutile / tree-shaking
- 🛠️ KPI : Total Blocking Time < 200 ms

---

### Story 7 : Chargement différé des composants

**En tant que** visiteur,  
**je veux** que les fonctionnalités secondaires soient chargées uniquement lorsque j'en ai besoin  
**afin de** accélérer l'affichage initial de l'application.  

- 🎯 Objectif : implémenter le lazy loading sur les pages secondaires
- 🧱 BP associée : chargement à la demande
- 🛠️ KPI : réduction de 50 % du bundle initial

---

### Story 8 : Réduction du poids du bundle React

**En tant que** utilisateur,  
**je veux** que l'application télécharge moins de code au démarrage  
**afin de** limiter le temps de chargement et la consommation énergétique.  

- 🎯 Objectif : bundle principal < 300 Ko compressé
- 🧱 BP associée : optimisation des dépendances
- 🛠️ KPI : taille du bundle analysée avec Webpack Bundle Analyzer

---

### Story 9 : Mise en cache des ressources

**En tant que** utilisateur récurrent,  
**je veux** que les ressources déjà téléchargées soient réutilisées lors de mes prochaines visites  
**afin de** éviter des téléchargements inutiles.  

- 🎯 Objectif : taux de cache supérieur à 90 %
- 🧱 BP associée : cache navigateur
- 🛠️ KPI : diminution du trafic réseau sur les visites répétées

---

###  Story 10 : Optimisation des appels API

**En tant que** utilisateur,  
**je veux** que seules les données nécessaires soient récupérées depuis le serveur  
**afin de** réduire les échanges réseau inutiles.  

- 🎯 Objectif : réduire de 80 % le volume des réponses API
- 🧱 BP associée : sobriété des flux de données
- 🛠️ KPI : taille moyenne des réponses API

---

###  Story 11 : Amélioration de l'EcoIndex

**En tant que** responsable du produit,  
**je veux** améliorer l'empreinte environnementale de l'application  
**afin de** réduire son impact écologique.  

- 🎯 Objectif : passer d'un EcoIndex D à B minimum
- 🧱 BP associée : démarche globale d'éco-conception
- 🛠️ KPI : EcoIndex > 65

---


### Story 12 : Amélioration de la sobriété visuelle de l'application

**En tant que** utilisateur récurrent,  
**je veux** que les visuels du dashboard soient sobres et que les animations fassent moins mal aux yeux
**afin de** économiser de la data sur mon forfait et de favoriser une application plus sobre et simple.

- 🎯 Objectif : supprimer les animations visuelles inutiles
- 🧱 BP associée : suppression d'animations js ou css lourdes et inutiles
- 🛠️ KPI : temps de chargement de la page réduit de 90%

---

