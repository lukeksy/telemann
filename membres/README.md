# Telemann — Espace Membres

Page d'information pour les membres du Chœur et Orchestre de Chambre Telemann.

## Stack

- **Runtime** : Node.js ≥ 18
- **Framework** : Express
- **Frontend** : HTML / CSS / JS vanilla (aucune dépendance côté client)

## Démarrage local

```bash
npm install
npm start
# → http://localhost:3000
```

## Déploiement sur Hostinger (Node.js Web App)

1. Pousser ce dépôt sur GitHub (`telemann` ou un repo dédié).
2. Dans le panneau Hostinger, créer une **Web App Node.js**.
3. Relier le dépôt GitHub et définir :
   - **Start command** : `node server.js`
   - **Node version** : 18+
4. Définir la variable d'environnement `PORT` si nécessaire (Hostinger l'injecte souvent automatiquement).
5. Déployer.

## Mise à jour du contenu

Tout le contenu est dans **`public/index.html`**.  
Pour mettre à jour un programme, une date ou un lien, éditez ce fichier puis faites un `git push` — Hostinger redéploiera automatiquement si le déploiement continu est activé.

### Liens à compléter

- Section **Partitions** : remplacer les `href="#"` par les vrais liens (Drive, Dropbox, etc.)
- Section **Divers** : le lien vers l'historique pointe actuellement sur la page Notion publique.
