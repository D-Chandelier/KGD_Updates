# 🧭 DWG Viewer  
> Visualiseur DXF/DWG moderne avec extraction et gestion avancée des textes

### 📸 Captures d’écran

<p align="center">
  <img src="https://raw.githubusercontent.com/D-Chandelier/KGD_Updates/main/DWG_Viewer/src/DWG_Viewer_Black.png" alt="DWG Viewer - Thème Sombre" width="25%" style="border-radius:12px; margin-right:4px;">
  <img src="https://raw.githubusercontent.com/D-Chandelier/KGD_Updates/main/DWG_Viewer/src/DWG_Viewer_Light.png" alt="DWG Viewer - Thème Clair" width="25%" style="border-radius:12px;">
</p>

<p align="center">
  <em>Thèmes Sombre et Clair du DWG Viewer</em>
</p>


---

### 📘 Présentation

**DWG Viewer** est une application Windows développée en **C# / WPF**, permettant d’ouvrir, afficher et interagir avec des fichiers **DXF** — et **DWG** via conversion automatique grâce à **ODA File Converter** (à installer séparément).

L’objectif est d’offrir un outil rapide et intuitif pour :
- Visualiser le contenu complet d’un dessin DXF/DWG  
- Interagir avec les entités de type **TEXT** et **MTEXT**  
- Sélectionner, copier et retraiter efficacement les textes pour les réutiliser dans d’autres logiciels  
- Explorer les calques, les blocs, les insertions, et bien plus  

---

### ⚙️ Fonctionnalités principales

✅ Lecture directe des fichiers **DXF**  
✅ Conversion automatique des **DWG → DXF** (via *ODA File Converter*)  
✅ Rendu vectoriel haute performance avec **SkiaSharp**  
✅ Interaction sur les entités textuelles (copie, sélection multiple, regroupement, etc.)  
✅ Gestion complète des calques et de la visibilité  
✅ Zone d’aperçu dynamique et panneau d’informations contextuelles  
✅ Mises à jour automatiques via **AutoUpdater.NET**  
✅ Stockage des préférences utilisateur en **JSON**  
✅ Interface moderne et légère avec **Material.Icons.WPF**

---

### 🧩 Technologies principales

| Composant | Description |
|------------|--------------|
| **C# / WPF (.NET 8)** | Application principale |
| **SkiaSharp.Views.WPF** | Rendu graphique DXF haute performance |
| **netDxf** | Lecture et parsing des fichiers DXF |
| **Material.Icons.WPF** | Icônes modernes et adaptatives |
| **System.Text.Json** | Stockage des préférences et configuration |
| **AutoUpdater.NET.Official** | Gestion des mises à jour |
| **ODA File Converter** | Conversion DWG → DXF (outil externe requis) |

---

### 🪟 Installation

1. **Téléchargez la dernière version** :  
   👉 [DWG_Viewer.zip](https://github.com/D-Chandelier/KGD_Updates/blob/main/DWG_Viewer/Latest/DWG_Viewer.zip)

2. **Décompressez et lancez `DWG_Viewer.exe`**

3. (Optionnel) Installez **ODA File Converter** et indiquez le chemin de l’exécutable dans les **options** du programme pour activer la compatibilité DWG.

---

