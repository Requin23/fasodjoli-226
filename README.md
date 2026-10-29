# fasodjoli-226
Plateforme open source d'alerte médicale et de gestion intelligente des dons de sang d'urgence au Burkina Faso — Hackathon 226.
# 🩸 FasoDjoli 226

> **Plateforme open source d'alerte médicale intelligente et de ciblage des dons de sang d'urgence au Burkina Faso.**

---

## 📌 Présentation du Projet
**FasoDjoli** (*"Le sang du Faso"*) est une solution numérique conçue pour répondre à la pénurie critique de poches de sang dans les formations sanitaires (CHU, CHR, CSPS) du Burkina Faso.

Contrairement aux appels à l'aide informels diffusés sur les réseaux sociaux (WhatsApp, Facebook), **FasoDjoli** met en place un **système d'alerte ciblé à boucle fermée** basé sur la géolocalisation et le groupe sanguin, garantissant une réponse rapide et la clôture automatique des demandes dès qu'un donneur se déplace.

---

## 🎯 Fonctionnalités Clés
- **Système d'Alerte Intelligente :** Notifications ciblées (PWA + Relais SMS/USSD) envoyées uniquement aux donneurs compatibles et situés à proximité.
- **Boucle Fermée & Clôture Automatique :** Désactivation immédiate de l'alerte dès confirmation du nombre de donneurs requis pour éviter les déplacements inutiles.
- **Architecture Offline-First :** Fonctionnement continu des centres de santé en cas de rupture de la connexion internet.
- **Respect de la Donnée & Délais Légaux :** Anonymisation des profils et gestion automatique du délai de carence (3 mois) entre deux dons.

---

## 🛠️ Stack Technique Envisagée
- **Front-end :** Vue.js / Progressive Web App (PWA)
- **Back-end :** Node.js / Express
- **Base de données :** PostgreSQL / SQLite (Offline caching)
- **Notifications :** Web Push API & Gateway SMS (API Open Source)
- **Hébergement & CI/CD :** Docker, Vercel / Serveurs Nationaux souverains

---

## 👥 Équipe AuraTech (Hackathon 226 - Édition 2026)
- **Aziz Farick ZALA** — *Lead Développeur & Concepteur Logiciel*
- **Bonaventure SAWADOGO** — *Spécialiste Déploiement Réseau & PWA*
- **Salim Sa Fadel TRAORÉ** — *Développeur Back-End & Base de Données*

---

## 📄 Licence
Ce projet est distribué sous licence Open Source **MIT**.
