# annotation_monte_cristo

> Groupe : Xinhao Zhang, Kexin Gui, Sandra Jagodzinska, Léna Gaubert

Il s'agit du projet d'évaluation d'annotateurs automatiques réalisé lors du cours *Enrichissement de corpus* donné par Iris Taravella en M1 TAL à Paris Nanterre (2022-2023). 
On a évalué ici trois annotateurs différents : Spacy (module de Python), Treetagger et SEM.

Ce dépôt github contient l'ensemble de notre projet : 

- `data` : dossier contenant tous les fichiers .csv avec les données des différents annotateurs, ainsi que les golds obtenus pour chacun d'entre eux.
	- format nom : `annotateur_output.csv` et `annotateur_output_gold.csv`
- `monte_cristo.txt` : extrait issu du roman *Le Comte de Monte-Cristo* d'Alexandre Dumas, utilisé ici pour les annotations.
- `annotation_monte_cristo.ipynb` : notebook principal avec annotation sur spacy, et résultats des annotations sur Treetagger et SEM.
- `confusion_matrix.ipynb` : script pour génération de la matrice de confusion pour l'annotation des parties du discours.

Enfin, `rapport.pdf` contient notre rapport final, explicitant notre méthodologie, nos résultats et analyses.
