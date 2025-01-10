
# AYouM - Plateforme E-commerce pour Montres Intelligentes

AYouM est une plateforme e-commerce moderne dédiée à la vente de montres intelligentes. Elle offre une interface intuitive, une navigation fluide, et un accès facile aux détails des produits, permettant aux utilisateurs de parcourir et d’acheter des montres en ligne sans effort.

## Fonctionnalités

- 🌟 **Interface conviviale** : Design propre et réactif pour une meilleure expérience utilisateur.
- 🛒 **Catalogue de produits** : Affichage des montres intelligentes avec leurs caractéristiques et prix.
- ✉️ **Messagerie et commentaires** : Les utilisateurs peuvent envoyer des messages et laisser des commentaires.
- 📂 **Gerer le panier** : Les utilisateurs peuvent gérer leurs interactions sans besoin de panier.

## Technologies utilisées

- **HTML5**, **CSS3**, **TailwindCSS**
- **JavaScript** pour l’interactivité
- **JSON (API fictive)** pour les données simulées
- Hébergement sur **GitHub Pages**

## Prérequis

Avant de commencer, assurez-vous d’avoir les éléments suivants installés :
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) pour exécuter et tester certaines fonctionnalités.
- Un navigateur web moderne

## Installation et Utilisation

### Étapes pour installer et exécuter le projet localement

1. Clonez le dépôt :
   ```bash
   git clone https://github.com/ayaachl/AYoumProjet.git
   ```

2. Accédez au répertoire du projet :
   ```bash
   cd AYoumProjet
   ```

3. Installez les dépendances nécessaires (si applicable) :
   ```bash
   npm install
   ```

4. Démarrez le serveur pour la fake API JSON :
   Assurez-vous que votre fichier JSON est prêt (par exemple, `db.json`).
   Lancez le serveur JSON en utilisant `json-server` :
   ```bash
   npx json-server --watch db.json --port 3000
   ```
   Cela démarre un serveur local pour votre API simulée sur `http://localhost:3000`.

   Si vous n’avez pas `json-server` installé, ajoutez-le avec la commande suivante :
   ```bash
   npm install -g json-server
   ```

5. Ouvrez le projet dans votre navigateur.
