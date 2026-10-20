# RILIFLIGHT — version professionnelle statique

## Ce que cette version fait réellement
- Interface responsive pour iPhone et ordinateur.
- Recherche aller-retour, aller simple et retour simple via un moteur externe.
- Paramètres de départ, destination, dates, voyageurs, budget cible et bagage à vérifier.
- Enregistrement local des recherches.
- Historique manuel des prix observés, statut du bagage, source et notes.
- Export CSV de l'historique.
- Comparaison arithmétique d'un aller-retour avec deux billets simples.
- PWA de base avec manifeste et cache hors ligne.

## Ce qu'elle ne fait pas
- Aucun accès à un flux de tarifs aériens.
- Aucun prix inventé ou affiché comme s'il était en direct.
- Aucune surveillance automatique des tarifs.
- Aucune notification en arrière-plan.
- Aucune réservation ni paiement.
- Les données sont stockées dans le navigateur local et ne se synchronisent pas entre appareils.

## Déploiement GitHub Pages
1. Téléverser tous les fichiers à la racine du dépôt.
2. Paramètres → Pages.
3. Source : déployer à partir d'une branche.
4. Branche `main`, dossier `/(root)`, puis enregistrer.
5. Ouvrir l'adresse Pages indiquée par GitHub.

## Pour de vrais tarifs et alertes
Il faut intégrer une API de recherche aérienne dont les conditions autorisent cet usage, gérer les clés API côté serveur, créer un backend et planifier les vérifications. Ne placez jamais une clé secrète dans `index.html`.
