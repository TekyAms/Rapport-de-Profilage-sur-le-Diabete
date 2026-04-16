# Rapport de Profilage sur le Diabète 🏥

Analyse complète et rapport de profilage sur les données de diabète. Ce projet combine une analyse exploratoire détaillée avec un rapport HTML interactif généré automatiquement.

## 📋 Contenu du Projet

- **`Analyse_du_diabetes.ipynb`** - Notebook Jupyter contenant l'analyse exploratoire des données (EDA)
- **`diabetes (1).csv`** - Dataset contenant les données brutes sur le diabète
- **`images/`** - Captures d'écran du rapport de profilage
- **`.gitignore`** - Configuration pour ignorer les fichiers non essentiels

## 🚀 Démarrage Rapide

### Prérequis
- Python 3.8+
- Jupyter Notebook
- Bibliothèques : pandas, numpy, matplotlib, seaborn, ydata-profiling

### Installation

```bash
# Cloner le repository
git clone https://github.com/TekyAms/Rapport-de-Profilage-sur-le-Diabete.git
cd Rapport-de-Profilage-sur-le-Diabete

# Installer les dépendances
pip install pandas numpy matplotlib seaborn jupyter ydata-profiling
```

### Exécution

```bash
# Lancer Jupyter Notebook
jupyter notebook Analyse_du_diabetes.ipynb
```

Exécutez les cellules du notebook pour générer le rapport interactif `rapport_profiling_diabete.html`, puis ouvrez-le dans votre navigateur.

## 📊 Données

Le dataset contient **768 observations** avec les variables suivantes :
- **Pregnancies** : Nombre de grossesses
- **Glucose** : Concentration de glucose (mg/dL)
- **BloodPressure** : Tension artérielle (mmHg)
- **SkinThickness** : Épaisseur des plis cutanés (mm)
- **Insulin** : Niveau d'insuline (µU/mL)
- **BMI** : Indice de masse corporelle
- **DiabetesPedigreeFunction** : Historique familial de diabète
- **Age** : Âge en années
- **Outcome** : Présence de diabète (0 ou 1)

## 🔍 Analyses Effectuées

✓ Analyse statistique descriptive complète  
✓ Distribution des variables et détection d'anomalies  
✓ Corrélations et relations entre variables  
✓ Identification des valeurs manquantes et aberrantes  
✓ Visualisations des patterns et tendances  

## 📈 Résultats

Le notebook génère un rapport de profilage HTML interactif avec :
- Statistiques détaillées par variable
- Distributions et histogrammes
- Matrice de corrélation
- Détection des anomalies
- Analyse de la qualité des données

## � Aperçu du Rapport

Voici des captures d'écran du rapport de profilage généré :

### Statisques Générales
![Statistiques générales](images/stats_generales.png)

### Distribution des Variables
![Distribution](images/distribution.png)

### Corrélations
![Corrélations](images/correlations.png)



## �💡 Structure du Notebook

1. **Chargement des données** - Import du CSV et aperçu initial
2. **Exploration descriptive** - Statistiques et structure
3. **Détection des anomalies** - Valeurs manquantes et zéros problématiques
4. **Analyse statistique** - Statistiques détaillées par colonne
5. **Génération du rapport** - Création automatique du fichier HTML

## 🛠️ Technologies Utilisées

- **Pandas** - Manipulation et analyse des données
- **NumPy** - Calculs numériques
- **Matplotlib & Seaborn** - Visualisations
- **YData Profiling** - Rapport de profilage automatique
- **Jupyter Notebook** - Environnement interactif

## 📝 Notes Importantes

- Le fichier `rapport_profiling_diabete.html` est généré **localement** en exécutant le notebook
- Les zéros dans certaines colonnes (Glucose, BloodPressure, etc.) représentent des valeurs manquantes ou non mesurées


## 📄 Licence

Ce projet est à usage libre.

## 👤 Auteur

**Tèkiyath AMOUSSA alias TekyAms** 

---

**💬 Pour en savoir plus** : Consultez le notebook Jupyter pour une analyse détaillée ou exécutez-le pour générer le rapport HTML complet.
