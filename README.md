# 🚗 3C's Generator - Assistant IA pour Notes Technicien Automobile

Un outil web léger, rapide et intelligent conçu spécifiquement pour les ateliers mécaniques et concessions automobiles. Il transforme instantanément les notes brutes d'un technicien en un rapport structuré standardisé au format **3 C's** (*Complaint, Cause, Correction*) grâce à l'API **Google Gemini 3.6 Flash**.

---

## 🌟 Fonctionnalités Principales

* ⚡ **Génération IA Ultra-Rapide** : Analyse et structure les notes de service en un clic.
* 🔠 **Formatage Spécifique Atelier** :
  * **STRICTEMENT EN MAJUSCULES** pour s'intégrer directement dans vos logiciels de gestion (DMS / ERA / PBS / Reynolds).
  * **Option Sans Accents (FR)** pour éviter tout problème d'encodage sur les systèmes legacy.
  * Conservation exacte de la ponctuation standard.
* 🔄 **Traduction Instantanée** : Basculez le rapport généré entre le **Français** et l'**Anglais** en un seul clic, sans retaper les notes.
* 💾 **Sauvegarde Locale Automatique** : Grâce au `localStorage`, vos données, votre langue et vos derniers résultats restent sauvegardés même si la page est fermée ou rafraîchie.
* 📜 **Historique Récent** : Conserve automatiquement les 5 dernières requêtes pour une consultation ou réutilisation rapide.
* 📋 **Copie en 1 Clic** :
  * Cliquez sur n'importe quel champ pour le copier directement dans votre presse-papier.
  * Bouton **"COPIER TOUT"** pour exporter l'ensemble du rapport (Complaint + Cause + Correction).
* 🌙 **Mode Sombre / Clair** : Thème visuel adaptatif pour un confort visuel dans tous les environnements de travail.
* ⌨️ **Raccourcis Clavier** : Lancement rapide avec `Ctrl + Entrée` (ou `Cmd + Entrée`).

---

## 🛠️ Technologies Utilisées

* **HTML5 / CSS3** (CSS Variables, Flexbox, Design Réponsif)
* **JavaScript Plain (ES6+)** (Aucune dépendance ni framework lourd requis)
* **Google Gemini API** (`gemini-3.6-flash`)

---

## 🚀 Installation & Utilisation

1. **Cloner le dépôt** :
   ```bash
   git clone [https://github.com/votre-utilisateur/3ccc.git](https://github.com/votre-utilisateur/3ccc.git)
