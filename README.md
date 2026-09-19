# 🇨🇲 MboaNkap

> **L'épargne qui nous rassemble.**

Application mobile de gestion de tontines pour le Cameroun.

[![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)
[![Flutter](https://img.shields.io/badge/Flutter-3.47-02569B?logo=flutter)](https://flutter.dev)
[![Dart](https://img.shields.io/badge/Dart-3.5-0175C2?logo=dart)](https://dart.dev)
[![Status](https://img.shields.io/badge/Status-MVP%20en%20cours-yellow)]()

---

## 📖 À propos

**MboaNkap** est une application mobile qui digitalise la gestion des tontines (njangi) au Cameroun. Elle permet à des groupes d'épargne de gérer leurs membres, cotisations, calendriers de tours et paiements en toute sécurité.

**Mboa** = *pays / chez nous* (argot camerounais)
**Nkap** = *argent* (argot camerounais)

---

## 🎯 Problème résolu

Les tontines camerounaises sont gérées manuellement (cahiers, carnets), ce qui entraîne :

- ❌ Pertes et erreurs de calcul
- ❌ Absence de traçabilité
- ❌ Litiges fréquents
- ❌ Détournement par le caissier
- ❌ Exclusion de la diaspora

**MboaNkap** apporte une solution **simple, sécurisée et transparente**.

---

## ✨ Fonctionnalités

### 🎯 MVP (en développement)
- [x] Authentification par téléphone + OTP
- [x] Création de compte avec PIN
- [ ] Gestion des tontines
- [ ] Gestion des membres
- [ ] Cotisations via MTN MoMo / Orange Money
- [ ] Rappels SMS / WhatsApp
- [ ] Calendrier des tours
- [ ] Reçus électroniques avec QR code
- [ ] Multi-niveaux de validation (anti-fraude)
- [ ] Historique et journal d'audit

### 🚀 V1 (à venir)
- [ ] Objectifs d'épargne
- [ ] MboaScore (score de confiance)
- [ ] Transferts entre membres
- [ ] Bot WhatsApp Business
- [ ] Statistiques avancées
- [ ] Mode diaspora

### 🔮 V2 (plus tard)
- [ ] IA anti-fraude
- [ ] Prédiction de trésorerie
- [ ] USSD pour zones rurales
- [ ] Multi-devises (CEMAC)

---

## 🛠️ Stack technique

| Couche | Technologie |
|---|---|
| **Mobile** | Flutter (Dart) |
| **Backend** | NestJS (TypeScript) |
| **Base de données** | PostgreSQL |
| **Cache** | Redis |
| **Paiement** | MTN MoMo API, Orange Money API |
| **Notifications** | WhatsApp Business Cloud API, SMS |
| **IA** | Python (FastAPI, scikit-learn) |
| **Stockage** | MinIO / S3 |

---

## 📁 Structure du projet

---

MboaNkap/
├── mobile/          # Application Flutter
├── backend/         # API NestJS
├── ai/              # Modules IA (Python)
├── web/             # Site web (React)
├── docs/            # Documentation
└── README.md

---

---

## 🎨 Charte graphique

| Couleur | Code | Usage |
|---|---|---|
| 🟢 Vert émeraude | `#0F8A5F` | Primaire |
| 🟡 Or | `#E8B33D` | Secondaire |
| ⚫ Anthracite | `#1F2A24` | Texte |
| ⚪ Fond clair | `#FAFAF7` | Arrière-plan |

**Polices :** Poppins (titres) + Inter (corps)

---

## 🚀 Installation

### Prérequis

- Flutter 3.19+
- Dart 3.5+
- Node.js 20+
- PostgreSQL 15+
- Android Studio

### Lancer l'app

```bash
# Cloner le projet
git clone https://github.com/arthurpone98-sketch/MboaNkap.git
cd MboaNkap/mobile

# Installer les dépendances
flutter pub get

# Lancer sur émulateur/téléphone
flutter run

---

Roadmap

· Septembre 2026 : Configuration de l'environnement ✅
· Octobre 2026 : Développement du MVP (Splash, Auth, Dashboard)
· Novembre 2026 : Paiements MoMo/OM, historique
· Décembre 2026 : Tests terrain avec 3 tontines pilotes
· Janvier 2027 : Publication PlayStore

---

👥 Équipe

· Arthur PONE — Fondateur & Développeur principal
  @arthurpone98-sketch

---

🤝 Contribuer

Les contributions sont bienvenues ! Voir CONTRIBUTING.md.

---

📄 Licence

Ce projet est sous licence GPL-3.0 — voir LICENSE.

---

📞 Contact

· 📧 Email : mboankapofficiel@gmail.com
· 🌐 Site : bientôt disponible
· 🐛 Bugs : Issues GitHub

---

<div align="center">

Fait avec ❤️ au Cameroun 🇨🇲

L'épargne qui nous rassemble.

</div>

---

