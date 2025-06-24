# Suivi des élèves – Grand Oral

Un tableau interactif en HTML, CSS et JavaScript pour gérer le **passage des élèves au Grand Oral**, conçu pour fonctionner **hors ligne** (aucune donnée envoyée sur un serveur) et **sans dépendance externe**.

## ✨ Fonctionnalités

* ⏱️ Insertion automatique de l'heure d'entrée (avec calcul automatique de l'heure de fin)
* 📅 Import de données via **CSV** ou **copier-coller**
* 🖊️ Modification manuelle possible des colonnes : salle, nom, prénom, heure de passage, heure d’entrée
* 🔄 Décompte automatique du temps restant
* 🔧 Durée par défaut réglable et personnalisable par ligne
* 🔃 Suspension automatique des mises à jour pendant l’édition
* 📌 Lignes actives affichées en haut, triées par temps restant
* 📂 Fonctionne entièrement dans un navigateur sans connexion

## 🖼️ Capture d’écran
![Capture d’écran du 2025-06-24 11-53-23](https://github.com/user-attachments/assets/0812325e-d97c-42a7-85db-6a0b58dbc492)

## 📄 Format CSV attendu

| Salle | Nom | Prénom | Heure de passage (HH\:MM) | Heure d'entrée (HH\:MM\:SS, optionnelle) |
| ----- | --- | ------ | ------------------------- | ---------------------------------------- |

Chaque ligne peut ensuite être enrichie via l’interface web.

## 🔧 Utilisation

1. Ouvrir le fichier `index.html` dans un navigateur moderne (Chrome, Firefox…).
2. Coller vos données ou importer un fichier `.csv` dans la section ⚙️.
3. Utilisez les boutons :

   * 🕒 pour horodater l’entrée
   * ➕ pour ajouter une ligne
   * ❌ pour supprimer une ligne
4. Le tableau se met à jour automatiquement, sauf lors de l’édition.

## ✅ Licence

Distribué sous licence [MIT](LICENSE).
