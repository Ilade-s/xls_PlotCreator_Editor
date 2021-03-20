# xls_PlotCreator
Créateur de plots (matplotlib) à partir de données d'un fichier xls
----------
Module pouvant être utlisé dans d'autres programmes, utilisant matplotlib afin de créer des graphiques sur les données d'un fichier xls, lu avec le module xlrd
----------
MODULES UTILISES (A INSTALLER) :
----------
    - xlrd (lecture de fichier xls)
    - matplotlib (graphiques)
FONCTIONS :
----------
    - DiagrammeBarres : Utlisant une seule colonne, va créer une graphique en barres
    - GrapheAxes : utlisant deux colonnes (x et y) créé un graphique y(x)
    - DiagrammeCirculaire : Utlisant une seule colonne, permet de comparer leur part dans la somme avec un camembert