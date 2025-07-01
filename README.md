# Projet Final Frontend

Bienvenue sur le frontend de votre projet final ! Ce projet est une application web moderne développée avec React et Tailwind CSS, permettant la gestion d'offres et de réservations.

## 🚀 Présentation

Cette application permet aux utilisateurs de :

- Consulter une liste d'offres
- Voir les détails d'une offre
- Créer, modifier et supprimer leurs propres offres
- Réserver des offres
- Gérer leurs réservations
- S'inscrire et se connecter

## 🖥️ Démo

Ajoutez ici un lien vers une démo en ligne ou une capture d'écran si disponible.

## 📦 Installation

1. **Cloner le dépôt**
   ```bash
   git clone <url-du-repo>
   cd frontend
   ```
2. **Installer les dépendances**
   ```bash
   npm install
   ```
3. **Lancer l'application**
   ```bash
   npm run dev
   ```
   L'application sera accessible sur [http://localhost:5173](http://localhost:5173) par défaut.

## 🗂️ Structure du projet

```
frontend/
├── public/               # Fichiers statiques
├── src/
│   ├── api/              # Gestion des appels API (axios)
│   ├── assets/           # Images et ressources statiques
│   ├── components/       # Composants réutilisables (Navbar, Footer, etc.)
│   ├── pages/            # Pages principales de l'application
│   ├── App.jsx           # Composant racine
│   └── main.jsx          # Point d'entrée de l'application
├── index.html            # Fichier HTML principal
├── package.json          # Dépendances et scripts
└── README.md             # Documentation
```

## 🛠️ Technologies utilisées

- [React](https://react.dev/) (Vite)
- [Tailwind CSS](https://tailwindcss.com/)
- [Axios](https://axios-http.com/)
- [JavaScript](https://developer.mozilla.org/fr/docs/Web/JavaScript)
- [Vite](https://vitejs.dev/)

## 🎨 Bonnes pratiques

- Respecter la structure des dossiers
- Utiliser des composants réutilisables
- Suivre les conventions de nommage (CamelCase pour les composants, kebab-case pour les fichiers)
- Utiliser des hooks React pour la gestion d'état et d'effets
- Centraliser les appels API dans `src/api/`

## 🤝 Contribution

Les contributions sont les bienvenues !

1. Forkez le projet
2. Créez une branche (`git checkout -b feature/ma-nouvelle-fonctionnalite`)
3. Commitez vos changements (`git commit -am 'Ajout d'une nouvelle fonctionnalité'`)
4. Poussez la branche (`git push origin feature/ma-nouvelle-fonctionnalite`)
5. Ouvrez une Pull Request

## 📄 Licence

Ce projet est sous licence MIT. Voir le fichier [LICENSE](LICENSE) pour plus d'informations.

---

_Développé dans le cadre du projet final._
