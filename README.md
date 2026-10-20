# RILIFLIGHT — PWA statique, sans dépendances

## Fonctions réellement opérationnelles
- Interface responsive adaptée à Safari/iPhone.
- Recherche externe datée pour les 8 directions CDG/ORY ↔ ALG/BJA.
- Sélection du départ, du retour, du séjour (14 à 21 jours) et du budget.
- Historique manuel local avec export CSV.
- Préférences locales pour les règles d'alerte.
- Manifest PWA, icône et service worker de cache.
- Aucun suivi analytique ou publicitaire intégré; aucun prix fictif affiché.

## Limites fonctionnelles explicites
- Aucun flux de tarifs aérien n'est connecté. Les recherches ouvrent Google Flights; l'app ne lit pas ses résultats.
- Aucun tarif réel n'est agrégé automatiquement.
- Aucune surveillance quotidienne en arrière-plan ni notification iOS n'est active.
- Les relevés sont stockés dans le navigateur de l'appareil; ils ne sont pas synchronisés.
- Les liens externes peuvent changer et doivent être vérifiés avant réservation.

## Publication gratuite
Déployer le contenu de ce dossier (index.html à la racine) sur un hébergement statique HTTPS, par exemple Cloudflare Pages ou GitHub Pages. Après publication, ouvrir l'URL dans Safari sur iPhone > Partager > Sur l'écran d'accueil > Ajouter.
Le service worker et l'installation PWA exigent HTTPS (sauf localhost).

## Confidentialité
Les paramètres et relevés restent dans localStorage. Ils peuvent être effacés par l'utilisateur ou lors de la suppression des données du navigateur. Exporter le CSV pour conserver une copie.
