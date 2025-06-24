# Analyse qualité avec FastQC sur Galaxy

Dans cette étape, nous allons évaluer la qualité des données RNA-seq en utilisant l’outil **FastQC** disponible sur Galaxy.

---

## 🎯 Objectifs

* Vérifier la qualité des lectures issues du séquençage RNA-seq.
* Identifier les problèmes potentiels tels que :

  * Bases de faible qualité.
  * Contamination par adaptateurs.
  * Distribution anormale des bases.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Accédez à [Galaxy Europe](https://usegalaxy.eu) et connectez-vous.

### 2. Importation des données

* Importez vos fichiers FASTQ en utilisant **Upload Data**.

### 3. Lancement de l’outil FastQC

* Recherchez et sélectionnez l'outil `FastQC` dans la barre d'outils Galaxy.
* Sélectionnez vos fichiers FASTQ importés précédemment.
* Conservez les paramètres par défaut et lancez l’analyse en cliquant sur **Execute**.

### 4. Consultation des résultats

* Une fois l’analyse terminée, ouvrez le rapport HTML généré.
* Examinez les résultats présentés sous forme graphique.

---

## 📊 Résultats attendus

Votre rapport FastQC inclura les sections suivantes :

* **Per base sequence quality** : Évalue la qualité moyenne des bases le long des lectures.
* **Per sequence quality scores** : Affiche la distribution globale des scores qualité des séquences.
* **Per base sequence content** : Révèle la distribution des nucléotides (A, T, C, G) à chaque position.
* **Per sequence GC content** : Indique la distribution du pourcentage en GC.
* **Adapter Content** : Identifie la présence éventuelle d'adaptateurs.

Interprétez ces résultats selon les indicateurs suivants :

* ✅ **Pass (vert)** : Bonne qualité, prêt pour l’étape suivante.
* ⚠️ **Warn (orange)** : Problèmes modérés nécessitant une étape de nettoyage (ex: trimming).
* ❌ **Fail (rouge)** : Problèmes graves nécessitant obligatoirement un prétraitement.



