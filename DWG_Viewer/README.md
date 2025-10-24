
v1.0.0.2 - 24/10/2025
========================
Version de teste pour confirmer le bon fonctionnement du système de MàJ

v1.0.0.1 - 23/10/2025
========================
L'application DWG_Viewer rapart sur une numérotation de version suite à une refonte complète du code 
et des fonctionnalités pour correspondre avec une logique de mise à jour plus conventionnelle.

Améliorations et Corrections Mineures:
--------------------------------------
- Correction d'un bug mineur dans l'affichage des entités DXF.
- Mise à jour des informations dans la fenêtre "A propos".
- Optimisation des performances lors du chargement des fichiers DXF volumineux.
- Amélioration de la stabilité générale de l'application.
- Mise à jour de la documentation utilisateur pour refléter les dernières modifications.
- Ajout de messages d'erreur plus clairs pour les fichiers DXF non pris en charge.
- Divers ajustements de l'interface utilisateur pour une meilleure expérience.

Nouvelle fonctionnalité:
------------------------
- Possibilité de configurer l'épaisseur des lignes via les paramètres de l'application.
- Impression ordonnée des entités DXF avec les textes au dessus pour une meilleur visibilité.
- Réorganision du QuadTree pour une meilleure gestion des entités lors de l'impression et du rendu.
- Ajout d'une fonction de mise à jour automatique de l'application.


Anciennes Versions:

v1.0.0.0 - 01/10/2025
========================
Informations sur l'Application DXFViewer
Version: 2.0a -> v1.0.0.0
Date de Publication: 23 Octobre 2025
Description:
DXFViewer est une application Windows développée en C# utilisant WPF pour l'interface utilisateur et 
la bibliothèque netDxf pour le traitement des fichiers DXF.

Fonctionnalités Principales:
- Ouverture et affichage des fichiers DXF.
- Support des entités DXF courantes telles que Line, Polyline, Circle, Arc, Text, MText, et plus.
- Navigation dans le dessin avec zoom et déplacement.
- Copie des entités sélectionnées dans le presse-papiers au format DXF.
- Interface utilisateur intuitive avec menus et options de configuration.

Crédits:
- Développé par [Votre Nom ou Nom de l'Équipe].
- Utilise la bibliothèque open-source netDxf.
- Merci à la communauté open-source pour leur soutien et leurs contributions.

Version 2.0a - 12/10/2025
========================
Améliorations et Corrections:
- Refonte majeur de la partie graphique pour une meilleure expérience utilisateur.
- Ajout et prise en compte des AttributeDefinitions (ATTDEF). [A pofiner]
- Amélioration en cours du rendu graphique des entités "Line" et "Polyline" pour prise en compte des pointillés.
  ( --- par defaut pour le moment à cause d'un ralentissement si utilisation du pattern Autocad.)
- Modification de la section "Presse Papier" pour limiter le blocage de l'interface lors de l'accès 
  au presse papier Windows.
- Ajout d'une fenêtre "A propos" avec les informations de version."
- Ajout d'une fenêtre "Aide" avec les instructions d'utilisation. Non renseigné mais prêt à l'emploi.
- Nettoyage du code pour améliorer la lisibilité et la maintenabilité.

Version 2.0 - 19/08/2025
========================
Améliorations et Corrections:

Polyline2DExtensions.cs:
	- Amélioration de la méthode `GetPolyline2D` pour gérer les polylignes avec des points de contrôle.
	- Prise en compte des polylignes ouvertes et fermées.
	- Correction du sens des Arcs pour les polylignes

ArcExtensions.cs:
	- Nettoyage du code pour améliorer la lisibilité.

MainWindow.xaml.cs:
	- Correction de la fonction ExitApp_Click() pour fermer l'application correctement.
	- Clic droit glissé pour sélection plusieurs lignes avec affichage du contextMenu
	- Mode RO, Ligne ou Multiligne
	 > mode RO: Interception du CTRL+V pour coller Cassette par Cassette

