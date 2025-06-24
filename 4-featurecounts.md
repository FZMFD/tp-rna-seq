# Comptage des lectures RNA-seq avec FeatureCounts

Cette étape consiste à compter le nombre de lectures RNA-seq alignées sur chaque gène, en utilisant l’outil **FeatureCounts** disponible sur Galaxy.

---

## 🎯 Objectifs

* Quantifier les lectures par gène.
* Générer une matrice de comptage nécessaire à l'analyse différentielle.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Connectez-vous à [Galaxy Europe](https://usegalaxy.eu).

### 2. Sélection de l'outil FeatureCounts

* Recherchez et ouvrez l'outil `FeatureCounts`.

### 3. Paramétrage de l’outil

* **Alignment file (BAM)** : Sélectionnez votre fichier BAM issu de HISAT2.
* **Gene annotation file (GTF)** : Choisissez le fichier GTF approprié correspondant à votre organisme de référence.
* **Strandedness** : Choisissez selon votre protocole expérimental (en général "Unstranded").
* Laissez les autres paramètres par défaut et cliquez sur **Execute**.

### 4. Vérification des résultats

* Une fois terminé, récupérez le fichier texte/tabulaire généré par FeatureCounts.

---

## 📊 Résultats attendus

Vous obtiendrez :

* Une matrice de comptage au format tabulaire, indiquant le nombre de lectures alignées par gène.
* Un résumé des statistiques de comptage.

---

## 🛠️ Prochaine étape

Après avoir obtenu les comptages, poursuivez vers l'analyse différentielle avec :

* [Analyse différentielle avec Limma ou DESeq2](./limma.md)

---

