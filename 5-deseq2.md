# Analyse différentielle avec Limma sur Galaxy

Dans cette étape, nous allons identifier les gènes différentiellement exprimés entre deux conditions expérimentales en utilisant l’outil **Limma** sur Galaxy.

---

## 🎯 Objectifs

* Identifier les gènes significativement différentiellement exprimés.
* Obtenir des informations statistiques sur les différences d’expression génique.

---

## 🚀 Étapes à suivre sur Galaxy

### 1. Connexion à Galaxy

* Connectez-vous à [Galaxy Europe](https://usegalaxy.eu).

### 2. Sélection de l'outil Limma

* Recherchez et sélectionnez l'outil `Limma`.

### 3. Paramétrage de l’outil

* **Input file** : Sélectionnez votre fichier de comptage (par exemple issu de FeatureCounts).
* **Design matrix** : Définissez les conditions expérimentales (traité vs contrôle) dans une matrice de design adaptée.
* **Contrast matrix** : Spécifiez les contrastes pour la comparaison entre conditions (par exemple, traité - contrôle).
* Vérifiez que les paramètres avancés sont conformes à votre design expérimental.
* Cliquez sur **Execute** pour lancer l’analyse.

### 4. Vérification des résultats

* Une fois terminé, consultez les résultats générés sous forme tabulaire.

---

## 📊 Résultats attendus

Vous obtiendrez :

* Une liste des gènes avec :

  * Log2 Fold Change (logFC)
  * Valeurs de p (p-value)
  * Valeurs ajustées (FDR ou adjusted p-value)
* Ces résultats permettent d’identifier clairement les gènes significativement exprimés différemment entre les conditions.

---
