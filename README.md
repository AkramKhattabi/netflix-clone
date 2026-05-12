🎬 Netflix Clone — React + Firebase
Un clone moderne de Netflix développé avec React.js et Firebase Authentication.
Ce projet reproduit l’expérience utilisateur de Netflix avec une interface élégante, une authentification sécurisée et une architecture frontend moderne.
🚀 Aperçu du Projet
Ce projet a été créé dans le but de pratiquer :
Le développement frontend moderne avec React
La gestion des composants et des états
L’authentification avec Firebase
Le routing avec React Router
L’intégration d’API pour récupérer des films et séries
La création d’une interface utilisateur responsive et immersive
L’application permet aux utilisateurs de :
✅ Créer un compte
✅ Se connecter / se déconnecter
✅ Parcourir des catégories de films
✅ Voir les affiches et bandes-annonces
✅ Naviguer dans une interface inspirée de Netflix
✅ Utiliser l’application sur desktop et mobile
🛠️ Technologies Utilisées
Technologie	Description
React.js	Frontend Library
Firebase	Authentification & Backend
React Router DOM	Navigation
CSS / Tailwind	Styling
TMDB API	Données films et séries
Axios	Requêtes HTTP
📸 Interface du Projet
Homepage






7
Authentication






6
📂 Structure du Projet
netflix-clone/
│
├── public/
├── src/
│   ├── components/
│   ├── pages/
│   ├── firebase/
│   ├── services/
│   ├── assets/
│   ├── App.js
│   └── main.jsx
│
├── package.json
└── README.md
⚙️ Installation
1️⃣ Cloner le Repository
git clone https://github.com/your-username/netflix-clone.git
2️⃣ Aller dans le dossier
cd netflix-clone
3️⃣ Installer les dépendances
npm install
4️⃣ Lancer le projet
npm run dev
ou
npm start
🔥 Configuration Firebase
Créer un projet sur :
Firebase Console
Puis ajouter les clés Firebase dans :
firebase.js
const firebaseConfig = {
  apiKey: "YOUR_API_KEY",
  authDomain: "YOUR_AUTH_DOMAIN",
  projectId: "YOUR_PROJECT_ID",
  storageBucket: "YOUR_STORAGE_BUCKET",
  messagingSenderId: "YOUR_SENDER_ID",
  appId: "YOUR_APP_ID"
};
🎥 API Films
Les données des films proviennent de :
TMDB API
Créer un fichier :
.env
Puis ajouter :
VITE_TMDB_API_KEY=YOUR_API_KEY
🔐 Fonctionnalités
✅ Authentification Firebase
Création de compte
Connexion utilisateur
Déconnexion
Gestion des sessions
✅ Interface Netflix
Hero Banner
Movie Rows
Hover Effects
Responsive Design
Navigation dynamique
✅ Gestion des Films
Films populaires
Tendances
Séries TV
Films d’action
Films d’horreur
Recherche dynamique
📱 Responsive Design
Le projet est entièrement responsive :
💻 Desktop
📱 Mobile
📲 Tablette
🧠 Objectifs Techniques du Projet
Ce projet permet de démontrer :
La maîtrise de React
L’intégration d’API REST
L’utilisation de Firebase Authentication
L’architecture moderne frontend
La gestion des composants réutilisables
Le responsive design avancé
🚀 Améliorations Futures
🎬 Lecteur vidéo
❤️ Système de favoris
🔎 Recherche intelligente IA
👤 Profils utilisateurs
🌙 Dark/Light Mode
🎞️ Recommandations personnalisées
☁️ Déploiement sur Vercel
☁️ Déploiement
Le projet peut être déployé facilement sur :
Vercel
Netlify
Firebase Hosting
📚 Ressources Utiles
React Documentation
Firebase Documentation
TMDB Developers
👨‍💻 Auteur
Akram Khattabi
Étudiant en MSc Big Data & AI — ECE Paris
⭐ Support
Si le projet vous plaît :
⭐ Star le repository
🍴 Fork le projet
🛠️ Contribuez librement
