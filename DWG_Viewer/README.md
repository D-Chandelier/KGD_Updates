# 🧭 DWG Viewer

---

## 📦 Version 1.0.0.1 — 23/10/2025

L'application **DWG Viewer** repart sur une numérotation de version suite à une **refonte complète du code** et des fonctionnalités, afin d'adopter une logique de mise à jour plus conventionnelle.

### ✅ Améliorations et Corrections Mineures

- Correction d'un bug mineur dans l'affichage des entités DXF.  
- Mise à jour des informations dans la fenêtre **À propos**.  
- Optimisation des performances lors du chargement de fichiers DXF volumineux.  
- Amélioration de la stabilité générale de l'application.  
- Mise à jour de la documentation utilisateur.  
- Messages d'erreur plus clairs pour les fichiers DXF non pris en charge.  
- Divers ajustements de l'interface pour une meilleure expérience utilisateur.

### ✨ Nouvelles Fonctionnalités

- Configuration de **l'épaisseur des lignes** via les paramètres de l'application.  
- **Ordre d'impression optimisé** : les textes sont dessinés au-dessus des autres entités.  
- **Réorganisation du QuadTree** pour une meilleure gestion du rendu et de l'impression.  
- Ajout d'une **fonction de mise à jour automatique** de l'application.

---

## 🕘 Anciennes Versions

### Version 1.0.0.0 — 01/10/2025

#### 📋 Informations sur l'application

- Nom : **DXFViewer**  
- Version précédente : 2.0a → 1.0.0.0  
- Date de publication : **23 octobre 2025**  
- Description :  
  DXFViewer est une application Windows développée en **C# (WPF)** utilisant la bibliothèque **netDxf** pour le traitement des fichiers DXF.

#### 🔧 Fonctionnalités principales

- Ouverture et affichage de fichiers DXF.  
- Support des entités : `Line`, `Polyline`, `Circle`, `Arc`, `Text`, `MText`, etc.  
- Navigation fluide : **zoom** et **panoramique**.  
- Copie d’entités sélectionnées dans le **presse-papiers DXF**.  
- Interface utilisateur intuitive avec menus et options de configuration.

#### 👏 Crédits

- Développé par **[Votre nom ou équipe]**  
- Utilise la bibliothèque open-source **netDxf**  
- Merci à la **communauté open-source** pour son soutien et ses contributions

---

### Version 2.0a — 12/10/2025

#### 🔨 Améliorations et corrections

- Refonte majeure de la partie graphique.  
- Ajout et prise en compte des **AttributeDefinitions (ATTDEF)** *(à peaufiner)*.  
- Amélioration du rendu graphique des entités **Line** et **Polyline** pour les motifs pointillés.  
  *(Les motifs AutoCAD complets restent désactivés pour cause de ralentissement)*  
- Modification de la section **Presse-papiers** pour éviter le blocage de l’interface.  
- Ajout d’une fenêtre **À propos** avec les informations de version.  
- Ajout d’une fenêtre **Aide** (préparée mais non renseignée).  
- Nettoyage global du code pour une meilleure maintenabilité.

---

### Version 2.0 — 19/08/2025

#### 🔧 Détails techniques

**`Polyline2DExtensions.cs`**
- Amélioration de `GetPolyline2D` pour gérer les points de contrôle.  
- Support des polylignes ouvertes et fermées.  
- Correction du sens des arcs pour les polylignes.

**`ArcExtensions.cs`**
- Nettoyage du code pour une meilleure lisibilité.

**`MainWindow.xaml.cs`**
- Correction de `ExitApp_Click()` pour une fermeture propre.  
- Clic droit + glissé : sélection multiple avec affichage d’un menu contextuel.  
- Modes d’édition :  
  - **RO** (lecture seule)  
  - **Ligne**  
  - **Multiligne**  
- En mode **RO**, interception de **Ctrl+V** pour coller *cassette par cassette*.

---

🧑‍💻 *DWG Viewer est un projet open-source destiné à offrir une visualisation DXF rapide, stable et moderne.*
