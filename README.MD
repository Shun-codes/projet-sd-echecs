# Projet DataSet sur les parties d’échecs 

## Date set utilisé : Lichess September 2020 data

### Structure du projet

Le projet doit contenir les fichiers suivants :
--- `Final_Analyse_python_BUT_2_A.ipynb` : Notebook contenant l’analyse des données et les résultats obtenus.
--- `LS-2020-DONNEES.csv` : Fichier contenant les données utilisées pour l'analyse, notamment le dataset de Lichess.
--- `README.MD` : Ce fichier, contenant comment lancée l'analyse python et ce qu'il faut installer pour le faire tourner.

### Instructions pour lancer l'analyse Python

1. **Téléchargement des fichiers** :
   - Assurez-vous d'avoir téléchargé les fichiers `Final_Analyse_python_BUT_2_A.ipynb` et `LS-2020-DONNEES.csv` dans le même répertoire sur votre machine.
   - Vous pouvez télécharger le CSV depuis Kaggle : https://www.kaggle.com/datasets/noobiedatascientist/lichess-september-2020-data/data?select=Sept_20_analysis.csv
   - Juste après le téléchargement, renommez le fichier CSV en `LS-2020-DONNEES.csv`.
   - Commande PowerShell (dans le dossier du projet) :

```powershell
Rename-Item .\Sept_20_analysis.csv LS-2020-DONNEES.csv
```

   - Commande Linux/macOS (dans le dossier du projet) :

```bash
mv Sept_20_analysis.csv LS-2020-DONNEES.csv
```

2. **Installation des dépendances** :
   - Assurez-vous d'avoir Python 3.x installé sur votre machine.
   - Ouvrez un terminal dans le dossier du projet puis installez les bibliothèques nécessaires :

```bash
pip install pandas matplotlib seaborn numpy scikit-learn jupyter
```

3. **Lancement du notebook** :
   - Toujours dans le dossier du projet, lancez Jupyter :

```bash
jupyter notebook
```

   - Dans votre navigateur, ouvrez `Final_Analyse_python_BUT_2_A.ipynb`.

4. **Exécution de l'analyse** :
   - Exécutez les cellules dans l'ordre, de haut en bas.
   - Vérifiez que le fichier `LS-2020-DONNEES.csv` est bien dans le même dossier que le notebook.

5. **Alternative avec VS Code** :
   - Ouvrez le dossier du projet dans VS Code.
   - Installez les extensions **Python** et **Jupyter** si nécessaire.
   - Ouvrez `Final_Analyse_python_BUT_2_A.ipynb` puis cliquez sur **Run All**.
  PS : C'est téllement mieux, c'est ce que nous avons utilisé pour faire le projet.

   - Si `pip` n'est pas reconnu, utilisez :
```bash
python -m pip install pandas matplotlib seaborn numpy scikit-learn jupyter
```
