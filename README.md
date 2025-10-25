# 🗂️ KGD Updates

> **Hub de mises à jour pour les applications développées par David Chandelier**  
> Chaque application dispose de son propre dossier avec les fichiers de mise à jour, exécutables et changelogs.

---

## 🚀 Applications disponibles

### 1️⃣ DWG Viewer
📂 Dossier : `DWG_Viewer/`  

**Description :**  
DWG Viewer est une application **WPF/C#** permettant de lire et interagir avec des fichiers **DXF** (et **DWG** via conversion ODA File Converter).  
Elle inclut :  
- 🖼️ Visualisation des fichiers DXF/DWG  
- ✏️ Sélection et copie intelligente des textes  
- 🧩 Support multi-calques, hatch, MText et inserts  
- ⚡ Rendu optimisé via **SkiaSharp**  
- 🔔 Mise à jour automatique avec **AutoUpdater.NET**

**Contenu du dossier :**  
- `Latest/` : dernière version compilée (`DWG_Viewer.zip`)  
- `Old/` : anciennes versions  
- `DWG_Viewer.xml` : fichier XML pour AutoUpdater.NET  
- `Changelog.md` : historique des versions  

**Téléchargement :**  
[📦 DWG_Viewer.zip](DWG_Viewer/Latest/DWG_Viewer.zip)  

**Changelog détaillé :**  
[📝 DWG_Viewer Changelog](DWG_Viewer/ChangeLog.md)  

---

## 🏗️ Structure du dépôt
KGD_Updates/  
|  
| -- DWG_Viewer/  
|  |-- Latest/ ← dernière version compilée  
|  |-- Old/ ← anciennes versions  
|  |-- Changelog.md ← historique des versions  
|  |-- DWG_Viewer.xml ← XML pour AutoUpdater.NET  
|  |-- LICENCE ← Licenses de DWG Viewer
|  |-- README.md ← spécifique à DWG Viewer  
|  |-- ThirdPartyLicenses.txt ← Détail des licences tiers
|  
|-- README.md ← ce fichier  


---

## 📜 Licences

- Les exécutables et fichiers de mise à jour sont **redistribuables** selon le fichier `LICENSE`.  
- Le **code source complet** est privé et n’est pas distribué ici.  
- Les dépendances NuGet sont mentionnées dans chaque application (`ThirdPartyLicenses.txt`).

---

## 🔮 Projets futurs

Ce dépôt est prévu pour accueillir **plusieurs programmes**.  
Chaque application aura sa propre structure isolée :  
- `Latest/` → dernière version compilée  
- `Old/` → anciennes versions  
- `Changelog.md` → historique des versions  
- XML → pour AutoUpdater.NET  

Objectif : **centraliser toutes les mises à jour** pour tes applications de manière publique et sécurisée.


---

## 🧑‍💻 Auteur

**David Chandelier**  
Développement C# / WPF  
📧 *Contact sur demande*

---

> 💡 *Ce dépôt est uniquement dédié aux fichiers de mise à jour. Le code source des applications reste privé.*

