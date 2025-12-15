# MN3 Labs – Portfolio sécurité

Portfolio web moderne présentant les projets de **MN3 Labs**, avec un focus
sur la sécurité applicative et le pentest.  
Ce site met en avant mes projets, notamment **SecureAuth**, ainsi que mes
compétences en développement et en sécurité.

## 🌐 Aperçu

- Page d’accueil avec design moderne (dark theme, glassmorphism)
- Page **Projets** avec une fiche détaillée pour **SecureAuth**
- Page **À propos** expliquant le contexte et les objectifs de SecureAuth
- Page **Compétences** (dev web + sécurité applicative)
- Page **Contact** (email, GitHub, téléphone)

## 🧪 Projet phare : SecureAuth

Projet présenté dans la page **Projets** :

- Système de Login/Register sécurisé en **PHP/MySQL**
- Hash des mots de passe avec `password_hash`
- Requêtes préparées (PDO) contre les injections SQL
- Protection **CSRF** sur plusieurs formulaires
- **Rate limiting** sur les tentatives de connexion
- Journalisation des tentatives + vue des logs
- Gestion de sessions, profil utilisateur, changement de mot de passe
  👉 Code source : https://github.com/mn3labs/SecureAuth

## 🛠 Stack technique

- **Frontend :**
  - HTML5
  - CSS3 (dark UI, glassmorphism)
  - [Bootstrap 5](https://getbootstrap.com/) pour la grille et les composants
  - JavaScript léger pour les petites interactions (année du footer, etc.)
- **Backend :**
  - Aucun backend pour le portfolio lui-même
  - Site **statique** (HTML/CSS/JS), facile à héberger
