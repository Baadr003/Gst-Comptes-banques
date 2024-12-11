# Application Frontend - Compte Client

## Description
Application React pour la gestion des comptes bancaires, permettant de créer, lister, modifier et supprimer des comptes.

## Structure du Projet
```
compte-client/
├── public/
│   ├── index.html
│   └── manifest.json
├── src/
│   ├── components/
│   │   ├── CompteForm.js     # Formulaire de création
│   │   ├── CompteList.js     # Liste des comptes
│   │   └── EditCompteModal.js # Modal de modification
│   ├── App.js                # Composant principal
│   ├── App.css               # Styles principaux
│   ├── index.js              # Point d'entrée
│   ├── index.css             # Styles globaux
│   └── config.js             # Configuration API
├── package.json
└── README.md
```

## Technologies Utilisées
- **React 17+**
- **Axios** pour les requêtes HTTP
- **React Bootstrap** pour les composants UI
- **Font Awesome** pour les icônes
- **CSS personnalisé** pour le style

## Configuration Requise
- **Node.js** (v14+)
- **npm** (v6+)

## Installation
```bash
# Cloner le dépôt
cd compte-client

# Installer les dépendances
npm install

# Démarrer en mode développement
npm start

# Construire pour la production
npm run build

# Lancer les tests
npm test
```

## Fonctionnalités

### 1. Liste des Comptes (CompteList.js)
- Affichage tabulaire des comptes
  - **Colonnes** : ID, Solde, Date de création, Type
  - **Actions** : Modifier et Supprimer
- Actualisation automatique après modifications

### 2. Création de Compte (CompteForm.js)
- Formulaire de création avec validation
  - **Champs** : Solde, Date de création, Type
- Feedback visuel (succès/erreur)
- `Loading state` pendant la soumission

### 3. Modification de Compte (EditCompteModal.js)
- Modal pour modification
- Pré-remplissage des données existantes
- Validation des entrées
- Confirmation de modification

### Vidéo démonstrative

https://github.com/user-attachments/assets/b0782f5a-43cc-4d4b-800f-1623c47b6d38

