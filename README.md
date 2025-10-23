# 🛡️ SafeDocs – Architecture Client-Serveur avec Supabase

Projet réalisé dans le cadre du TP "Conception, Déploiement et Sécurisation d'Architectures Web Modernes" pour l’entreprise fictive **DataSecure Corp**.

## 📌 Objectif

Développer une application web permettant aux utilisateurs de stocker et gérer leurs fichiers de manière sécurisée, en utilisant une architecture client-serveur avec Supabase.

## 🧱 Technologies utilisées

- **Frontend** : React  
- **Backend** : Supabase (Auth, Database, Storage)  
- **Sécurité** : Row Level Security (RLS), JWT, CORS  
- **Outils** : VS Code, Supabase CLI, Postman

## 🚀 Fonctionnalités

- 🔐 Authentification sécurisée via Supabase Auth  
- 📤 Upload de fichiers personnels  
- 📁 Affichage des fichiers de l’utilisateur connecté  
- 🔒 Sécurisation des accès avec RLS et policies Supabase

## ⚙️ Installation

### 1. Cloner le projet

```bash
git clone https://github.com/ferd203/SafeDocs-CS.git
cd SafeDocs-CS


2. Créer un projet Supabase
- Rendez-vous sur https://supabase.com
- Activez les modules : Auth, Database, Storage
- Copiez l’URL du projet et la clé anon dans un fichier .env
REACT_APP_SUPABASE_URL=https://your-project.supabase.co
REACT_APP_SUPABASE_ANON_KEY=your-anon-key


3. Lancer l’application
npm install
npm start


🔐 Sécurité
- ✅ Row Level Security activé
- ✅ Policies configurées pour restreindre l’accès aux fichiers
- ✅ CORS vérifié entre React et Supabase
- ✅ Tests réalisés avec Postman et OWASP ZAP
📂 Structure du projet
SafeDocs-CS/
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   └── supabaseClient.js
│   ├── .env.example
│   └── docker-compose.yml
├── .gitignore
└── README.md


📸 Aperçu
- Page de connexion
- Interface d’upload
- Liste des fichiers personnels
📜 Licence
Projet pédagogique réalisé dans le cadre d’un TP universitaire.
© 2025 – Ferdinand
