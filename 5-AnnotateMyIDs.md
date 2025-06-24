# Annotation des identifiants avec AnnotateMyIDs sur Galaxy

Cette étape vise à annoter les identifiants des gènes obtenus à partir de votre analyse RNA-seq avec l’outil **AnnotateMyIDs** sur Galaxy.

---

## 🎯 Objectifs

* Associer des identifiants de gènes à des annotations fonctionnelles.
* Faciliter l'interprétation biologique des résultats obtenus.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Connectez-vous à [Galaxy Europe](https://usegalaxy.eu).

### 2. Sélection de l'outil AnnotateMyIDs

* Recherchez et sélectionnez l'outil `AnnotateMyIDs`.

### 3. Paramétrage de l’outil

* **Input file** : Sélectionnez le fichier contenant les identifiants des gènes à annoter (typiquement le fichier de résultats issu de FeatureCounts ou d’analyse différentielle).
* **Select the species** : Choisissez votre organisme (ex : Homo sapiens, Arabidopsis thaliana).
* **Input ID type** : Indiquez le type d'identifiant que vous avez (par exemple, Ensembl ID, Gene Symbol).
* **Output fields** : Sélectionnez les annotations désirées (nom du gène, fonction, voie biologique, etc.).
* Cliquez sur **Execute** pour lancer l’annotation.

### 4. Vérification des résultats

* Une fois terminé, ouvrez et examinez le fichier d'annotations généré par AnnotateMyIDs.

---

## 📊 Résultats attendus

Vous obtiendrez :

* Un fichier annoté reliant chaque identifiant à des informations fonctionnelles telles que :

  * Nom complet du gène
  * Description fonctionnelle
  * Catégorie de voies biologiques (pathways)

---

## 🛠️ Prochaine étape

Après l'annotation, vous pourrez passer à :

* [Analyse approfondie et visualisation des résultats](./data-tables.md)

---
