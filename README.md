# 🛡️ ETHICAL – Framework de Pentest Éthique

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-Ethical--Use-red)
![Version](https://img.shields.io/badge/Version-3.0-green)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-lightgrey)

**Un outil complet de test d'intrusion éthique développé pour l'apprentissage et la démonstration en cybersécurité.**

<p align="center">
  <img src="https://img.shields.io/badge/Ethical-Hacking-brightgreen" alt="Ethical Hacking">
  <img src="https://img.shields.io/badge/Penetration-Testing-orange" alt="Penetration Testing">
  <img src="https://img.shields.io/badge/Cyber-Security-blue" alt="Cyber Security">
</p>

---

## 🎯 Table des Matières

- [📖 Description](#-description)
- [🚀 Fonctionnalités Principales](#-fonctionnalités-principales)
- [📦 Installation](#-installation)
- [🛠️ Utilisation](#️-utilisation)
- [📌 Dépendances](#-dépendances)
- [⚠️ Avertissements Importants](#️-avertissements-importants)
- [🔐 Sécurité](#-sécurité)
- [📸 Captures d’écran](#-captures-décran)
- [🌟 Fonctionnalités Avancées](#-fonctionnalités-avancées)
- [📋 Prérequis](#-prérequis)
- [🏢 Contexte Académique](#-contexte-académique)
- [📝 Licence](#-licence)
- [🤝 Contribution](#-contribution)
- [📞 Support](#-support)
- [🙏 Remerciements](#-remerciements)

---

## 📖 Description
**ETHICAL** est un **framework de test d’intrusion** développé par le **Groupe 44 – IUT Douala**.  
Il regroupe plusieurs fonctionnalités pour **apprendre, démontrer et pratiquer** la cybersécurité dans un environnement **contrôlé et autorisé**.

⚠️ **Avertissement :**  
Usage strictement **pédagogique et légal**. Toute utilisation malveillante est interdite.  
L’équipe de développement et l’IUT Douala déclinent toute responsabilité.

---

## 🚀 Fonctionnalités Principales

### 🔧 Préparation & Configuration
- Installation automatique des dépendances
- Informations système détaillées
- Détection de la plateforme (Windows, Linux, macOS)
- Vérification d’autorisation via système de licence
- Gestion sécurisée des clés de chiffrement

### 🎯 Génération de Payloads
- Payload Windows avec options de furtivité
- Payload Android (basique ou injection dans APK existant)
- Signature automatique des applications
- Options de personnalisation avancées

### 🔍 Reconnaissance
- Scanner réseau avancé avec détection d’OS
- Détection d’hôtes actifs par plusieurs méthodes
- Scan de ports et grabber de bannières
- Analyse de vulnérabilités web (XSS, SQLi, fichiers sensibles)

### ⚡ Post-Exploitation
- Listener TCP multiplateforme avec shell interactif
- Transfert de fichiers (upload/download)
- Craquage de mots de passe (MD5, SHA1, dictionnaire)
- Gestion de sessions persistantes et historique des commandes

### 📊 Reporting & Utilitaires
- Base de données SQLite intégrée
- Export des résultats (JSON, CSV, HTML, TXT)
- Journalisation complète des activités
- Gestion des logs détaillée

---
## 📦 Installation

```bash
# Cloner le dépôt
git clone https://github.com/TON-UTILISATEUR/ethical.git
cd ethical

# Lancer l'installation automatique
python3 ethical.py
# Sélectionner l'option [1] pour installer les dépendances
