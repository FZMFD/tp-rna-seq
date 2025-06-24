# Alignement des données RNA-seq avec HISAT2

Dans cette étape, nous allons aligner les lectures nettoyées RNA-seq sur un génome de référence à l'aide de l'outil **HISAT2** disponible sur Galaxy.

---

## 🎯 Objectifs

* Aligner les reads sur un génome de référence.
* Générer un fichier BAM nécessaire pour le comptage des lectures.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Connectez-vous à [Galaxy Europe](https://usegalaxy.eu).

### 2. Sélection de l'outil HISAT2

* Recherchez et ouvrez l'outil `HISAT2`.

### 3. Paramétrage de l’outil

* **Source for the reference genome** : Sélectionnez le génome de référence approprié (ex : Arabidopsis thaliana).
* **Single-end or paired-end reads?** : Choisissez selon votre type de données (single-end ou paired-end).
* **FASTQ file** : sélectionnez vos fichiers nettoyés (trimmed).
* Laissez les autres paramètres par défaut, puis cliquez sur **Execute**.

### 4. Vérification des résultats

* Attendez la fin de l'exécution et récupérez votre fichier BAM (alignement).

---

## 📊 Résultats attendus

Vous obtiendrez :

* Un fichier d'alignement (format BAM) prêt pour l'étape suivante.
* Un résumé indiquant les statistiques d’alignement (pourcentage d’alignement).

---

## 🛠️ Prochaine étape

Après l'alignement, continuez avec le comptage des lectures :

* [Comptage des reads avec FeatureCounts](./featurecounts.md)

---
