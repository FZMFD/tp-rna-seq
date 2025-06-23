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

Nous utiliserons les fichiers RNA-seq du projet **SRP101277** (Arabidopsis thaliana) :  

| Condition | Description            | Lien FASTQ direct (clique droit → copier l'adresse) |
|-----------|------------------------|-----------------------------------------------------|
| Contrôle  | Wild-type non traité   | https://sra-download.ncbi.nlm.nih.gov/traces/sra66/SRR/005419/SRR5309277/SRR5309277.fastq.gz |
| Traité    | Mutant mkp1 traité     | https://sra-download.ncbi.nlm.nih.gov/traces/sra66/SRR/005419/SRR5309278/SRR5309278.fastq.gz |

---

## 🧰 Plateforme utilisée

> 🔗 [Galaxy Europe](https://usegalaxy.eu)  
Galaxy est une plateforme web gratuite pour l’analyse de données de séquençage sans programmation.

---

## 🛠️ Étapes du TP

1. **Importation des données**
   - Depuis un lien partagé ou depuis l’outil FTP

2. **Contrôle qualité**
   - `FastQC` pour évaluer la qualité des lectures

3. **Pré-traitement**
   - `Trim Galore!` ou `Cutadapt` (si nécessaire)

4. **Alignement au génome**
   - Utilisation de `HISAT2` ou `STAR`

5. **Comptage des lectures par gène**
   - `FeatureCounts` avec une annotation `.gtf`

6. **Analyse différentielle**
   - `DESeq2` (galaxy wrapper)
   - Obtention de log2FC, p-value, volcano plot

7. **Visualisation**
   - Heatmap, MA-plot, table des gènes exprimés

---

## 📂 Ressources utiles

- 🔗 [Galaxy Training Material - RNA-seq](https://training.galaxyproject.org/training-material/topics/transcriptomics/)
- 📑 [Fiche technique DESeq2](https://bioconductor.org/packages/release/bioc/html/DESeq2.html)
- 📚 Référence article : Wang et al., RNA-Seq: a revolutionary tool for transcriptomics (2010)

---

## 📝 Consignes à suivre

- Créez un **compte Galaxy** si ce n’est pas déjà fait.
- Travaillez par binôme ou individuellement.
- Documentez chaque étape avec des **captures d’écran** et commentaires dans un rapport à rendre.
- Interprétez les gènes significativement exprimés et proposez des hypothèses biologiques.


