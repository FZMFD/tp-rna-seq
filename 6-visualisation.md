# TP : Analyse différentielle de l’expression génique RNA-seq avec DESeq2  
## Exemple sur *Arabidopsis thaliana*

---

## 🎯 Objectifs pédagogiques

- Comprendre les principes de l’analyse différentielle RNA-seq.
- Savoir identifier des gènes différentiellement exprimés (DEGs).
- Interpréter des résultats issus de DESeq2 (log2FoldChange, pvalue, padj…).
- Visualiser et discuter l’impact biologique potentiel.

---

## 📝 Jeu de données

- Fichier fourni : **rna_seq_deseq2_results.md** (ou .tsv/.csv)
- Colonnes disponibles :  
  - `gene_id` : identifiant du gène  
  - `log2FoldChange` : variation d’expression (log2)  
  - `pvalue` : p-value brute  
  - `padj` : p-value ajustée (FDR)  
  - `baseMean` : expression moyenne

---

## 🔍 Étapes d’analyse

1. **Filtrer les gènes significatifs**  
   - Critère classique : `padj < 0.05`
   - Prendre en compte aussi la variation (|log2FoldChange| > 1)

2. **Lister et classer les gènes**  
   - Les plus **up-régulés** (`log2FoldChange` > 1)
   - Les plus **down-régulés** (`log2FoldChange` < -1)

3. **Visualiser les résultats**  
   - Construction d’un **volcano plot** (optionnel)
   - Classement par importance biologique possible

4. **Discussion/interprétation**  
   - Quels gènes seraient intéressants à valider par qPCR ?
   - Certains gènes sont-ils déjà connus comme impliqués dans la condition étudiée ?
   - Quelles hypothèses peut-on faire sur leur rôle ?

---


