# Éditeur d'Arbre de Décision OSI

🛠️ Application web permettant de créer, éditer et exporter des arbres de décision organisés par couche OSI.  
Ce projet est particulièrement adapté à la documentation des diagnostics réseaux et procédures de résolution.

## ✨ Fonctionnalités

- Ajout, modification et suppression de couches OSI
- Ajout, édition et suppression graphique de questions/réponses
- Actions associées : passer à une autre couche, proposer une commande, appliquer une correction, etc.
- Import/export facile au format JavaScript (`const layers = {...}`)
- Import manuel via copier/coller
- Chargement et édition de fichiers `.html` contenant des structures `layers`
- Annulation des modifications avec restauration à l’état initial

## 🚀 Utilisation

1. Ouvrez le fichier `osi-editor.html` dans votre navigateur.
2. Cliquez sur **📁 Charger fichier HTML** ou **📋 Importer JS** pour démarrer.
3. Éditez visuellement votre arbre.
4. Exportez le résultat avec **💾 Exporter JS**.

## 📦 Export

L’arbre de décision est exporté sous la forme d’une variable JavaScript `const layers = {...}` que vous pouvez intégrer dans vos outils ou pages web.

## 🛡️ Licence

Ce projet est fourni sous une licence restreinte :

- **Usage personnel, associatif ou public autorisé**
- **Usage commercial strictement interdit**, même via une copie, un fork ou une dérivation

👉 Voir le fichier [`LICENSE`](LICENSE) pour les détails.

## 📫 Contact

Pour toute demande liée à l’utilisation ou à l’adaptation du projet, merci de me contacter via GitHub.
