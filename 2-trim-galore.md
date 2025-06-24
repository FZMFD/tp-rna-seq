# Prétraitement des données RNA-seq avec Trimmomatic

Dans cette étape, nous allons nettoyer les données RNA-seq brutes en utilisant l’outil **Trimmomatic** disponible sur Galaxy.

---

## 🎯 Objectifs

* Éliminer les bases de mauvaise qualité.
* Supprimer les adaptateurs de séquençage.
* Préparer les données pour l'alignement.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Connectez-vous à [Galaxy Europe](https://usegalaxy.eu).

### 2. Sélection de l'outil Trimmomatic

* Recherchez et ouvrez l'outil `Trimmomatic`.

### 3. Paramétrage de l’outil

* **Input FASTQ file** : sélectionnez votre fichier FASTQ à traiter.
* **Adapter clipping** : choisissez une option prédéfinie (par exemple, "Illumina universal").
* **Sliding window trimming** : activé, avec les paramètres standards (ex : 4 bases, qualité moyenne 20).
* **Minimum length** : définissez une taille minimale de reads acceptable (ex : 36 bases).
* Cliquez sur **Execute** pour lancer l’analyse.

### 4. Vérification des résultats

* Une fois terminé, récupérez les fichiers FASTQ nettoyés (output : trimmed FASTQ files).

---

## 📊 Résultats attendus

Vous obtiendrez :

* Un fichier FASTQ nettoyé (trimmed), sans adaptateurs et bases de faible qualité.
* Un rapport décrivant le nombre de reads supprimés et les opérations effectuées.

---
