NEXORA V1 — PREMIER PROTOTYPE

Ce dossier contient une première version web installable (PWA) de NEXORA.

CE QUI FONCTIONNE
- Navigation Accueil / Explorer / Créer / Favoris / Profil
- Recherche et filtres de Portals
- Fiche de présentation d'un Portal
- Création de Portals enregistrés localement sur l'appareil
- Favoris enregistrés localement
- Base PWA avec manifeste et service worker

LIMITES IMPORTANTES
- Ceci est un prototype frontend : il n'y a pas encore de comptes utilisateurs, serveur, messagerie réelle, vidéos hébergées, modération, paiement ni synchronisation entre appareils.
- Les Portals créés et favoris restent sur le même appareil/navigateur.
- Les images de démonstration utilisent des images distantes ; une connexion est nécessaire pour les charger.
- NEXORA PLUS est seulement présenté : aucun paiement n'est activé.

POUR TESTER
1. Décompresse le ZIP.
2. Héberge le dossier sur un hébergeur statique HTTPS (par exemple GitHub Pages ou Netlify).
3. Ouvre l'adresse HTTPS sur Android ou iPhone.
4. Android : menu du navigateur > Installer l'application / Ajouter à l'écran d'accueil.
5. iPhone : Safari > Partager > Sur l'écran d'accueil.

Pour une PWA complète, le site doit être servi en HTTPS. Ouvrir index.html directement ne permet pas toutes les fonctions PWA.

PROCHAINE ÉTAPE
Mettre le projet en ligne, puis ajouter une vraie base de données et des comptes. Ne collecte pas de données personnelles avant d'avoir mis en place sécurité, confidentialité et modération.
