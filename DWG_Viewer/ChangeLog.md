## 📚 v1.0.0.11 — 10/04/2026
### ✅ Correction de bug:
 - Problême de carractères de formatage des textes dans les attributs d'insert.
 - Modification des accès distants pour les mises à jours (blocage des liens "raw" par VPN).
 - Taille de la fenetre catalogue par defaut.

---

# 📜 Notes de version — DWG Viewer
| Criticités | Icônes | Signification | Descriptions |
|----------|:--:|----------------------------|----|
| Major    |🚀| Version majeure              | Changement radical, incompatible avec l’ancienne version.                    |
| Minor    |🧩| Version mineure              | Ajout de fonctionnalités **compatibles** avec la version précédente.         |
| Build    |✅| Build/patch                  | Corrections de bugs, petites améliorations, recompilation.                   |
| Revision |🧹| Révision / numéro de release | Modifications très mineures, hotfix, ou incrément automatique à chaque build.|


---
<details>
  <summary>Cliquer pour afficher l'historique des versions</summary>  

## 📚 v1.0.0.9 & v1.0.0.10 — 10/11/2025
### ✅ Correction de bug:
 - Problême de mise à l'échelle
<p align="center">
  <img src="https://github.com/D-Chandelier/KGD_Updates/releases/latest/download/1.0.0.9.png" width="50%" style="border-radius:12px; margin-right:4px;">
</p>

## 📚 v1.0.0.8 — 07/11/2025
### Améliorations:
 - 🧩 Début d'intégration du catalogue (Béta)
 - 🧹 Optimisation de conversion DWG->DXF en répertoire temporaire

## 📚 v1.0.0.7 — 07/11/2025
### Améliorations:
 - ✅ Empeche la selection des textes si le calques n'est pas visible
 
## 📚 v1.0.0.6 — 04/11/2025
### Améliorations: 
 - ✅ Correction du bug pour deplacement du plan avec rotation
 - 🏗️ Réorganisation du code

## 📚 v1.0.0.5 — 26/10/2025
### Améliorations: 
- 🚀 Rotation du plan **"⟲" "⟳"** dans la barre de statut
- 🧩 Fichier/Document info:  
  - Affichage des variables du document.
  - Affichage détaillé des calques.
  - Affichage des types de ligne.
  
## 📚 v1.0.0.4 — 26/10/2025
### Améliorations: 
- ✅ Correction du bug "clic simple" en mode RO
- 🚀 Ajout menu contextuel en mode Baie (B1 à B12)
- 🏗️ Création de classes pour séparer proprement le code
- 🧹 Nettoyage du code 

## 📚 v1.0.0.3 — 25/10/2025
### Améliorations mineurs 
- ✅ Mise en page de la fenêtre **Update**
- ✅ Verification de version via `Aide/Vérifier les mises à jour...`
- ✅ Mise aux normes du Github **KGD_Updates** pour respecter les recommandations de Github.
- ✅ Fenêtre `Aide/A Propos` adaptée pour refléter le Github.
- ✅ Intégration complète avec le nouveau système de mise à jour automatique.  

## 📚 v1.0.0.2 — 24/10/2025
### Objectif
Version de test destinée à **valider le bon fonctionnement du système de mise à jour automatique (AutoUpdater.NET)** avant déploiement officiel.

- 🧰 Stabilisation du moteur de rendu DXF.  
- ✅ Vérification du bon fonctionnement du téléchargement et de l’application des mises à jour.  
- 🔍 Ajustements mineurs dans les logs et le suivi des versions.

## 📚 v1.0.0.1 — 23/10/2025
### Refonte complète
L’application **DWG_Viewer** repart sur une **nouvelle base de versionnement** (v1.x) pour une meilleure gestion des mises à jour.

### Changements notables :
- 💾 Nouvelle structure interne pour une meilleure stabilité.  
- 📚 Amélioration du chargement des fichiers DXF volumineux.  
- 🧩 Optimisation de la lecture et de l’affichage des entités (Line, Text, MText…).  
- 🪶 Interface **“À propos”** et messages d’erreur mis à jour.  
- ⚙️ Intégration complète avec le fichier de configuration JSON (AppSettings).  
- 🌙 Préparation du support thème clair / sombre.  
- 🔔 Ajout du système de mise à jour automatique via **AutoUpdater.NET**.
</Details>

---

## 🕒 Historique
Chaque version publiée est packagée et disponible via le fichier `DWG_Viewer.xml` utilisé par l’application.  
Les fichiers de mise à jour sont hébergés dans ce dépôt public.

🔗 **Dernier package** : [DWG_Viewer.zip](https://github.com/D-Chandelier/KGD_Updates/releases/latest/download/DWG_Viewer.zip)

---

> 🛠️ *DWG Viewer continue d’évoluer : nouvelles optimisations, meilleure compatibilité avec les formats DXF/DWG et intégration continue des retours utilisateurs.*
