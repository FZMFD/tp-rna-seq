# 🧬 TP : Analyse de l’expression génique par RNA-seq avec Galaxy

---

## 🎯 Objectifs du TP

- Comprendre les étapes clés du pipeline RNA-seq.
- Utiliser Galaxy pour analyser des données RNA-seq (FASTQ) d’échantillons traités vs contrôles.
- Générer des résultats biologiquement interprétables (gènes différentiellement exprimés).
- Visualiser les résultats avec des outils intégrés.

---


## 📥 Téléchargement et importation des données

### 1. Télécharger les fichiers FASTQ (single-end) depuis SRA

Nous utiliserons les fichiers RNA-seq du projet **SRP101277** (Arabidopsis thaliana) 

## La plante contrôle  

-(https://drive.google.com/file/d/1exh1H7JpQ5lCoh4d9YnT_kGXcmwkgh1h/view?usp=drive_link)

## La plante traitée  

-(https://drive.google.com/file/d/1fB9h_TW9y5tFRjR7fWQ3_nEkyVMdYcPt/view?usp=drive_link)

---

## 🧰 Plateforme utilisée

> 🔗 [Galaxy Europe](https://usegalaxy.eu)  
Galaxy est une plateforme web gratuite pour l’analyse de données de séquençage sans programmation.

---

## Étapes du TP (cliquez pour accéder aux détails)

1. [Contrôle qualité - FastQC](./1-fastqc.md)  
2. [Pré-traitement - Trimmomatic!](./2-trim-galore.md)  
3. [Alignement - HISAT2](./3-hisat2.md)  
4. [Comptage - FeatureCounts](./4-featurecounts.md)
5. [Annotation - AnnotateMyIDs](./5-AnnotateMyIDs.md)
6. [Analyse différentielle - Limma](./5-deseq2.md)  
7. [Visualisation - MultiQC](./6-visualisation.md)


---

## 📝 Consignes à suivre

- Créez un **compte Galaxy** si ce n’est pas déjà fait.
- Travaillez par binôme ou individuellement.
- Documentez chaque étape avec des **captures d’écran** et commentaires dans un rapport à rendre.
- Interprétez les gènes significativement exprimés et proposez des hypothèses biologiques.


