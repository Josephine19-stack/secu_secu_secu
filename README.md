Analyse du jeu de données SWaT :

Utilisez le jeu de données  SWaT.A3_dataset_Jul 19_labelled.csv (au lien du SWaT.A7)
La documentation donne quelques éléments sur les attaques réalisées :  

[SWaT data collection_20-07-2019 v2.pdf]: https://epitafr.sharepoint.com/sites/PP-share/Documents%20partages/Forms/AllItems.aspx?id=%2Fsites%2FPP%2Dshare%2FDocuments%20partages%2FGeneral%2Fdatasets%2FWater%20treatment%2FSWAT%2FSWaT%20data%20collection%5F20%2D07%2D2019%20v2%2Epdf&parent=%2Fsites%2FPP%2Dshare%2FDocuments%20partages%2FGeneral%2Fdatasets%2FWater%20treatment%2FSWAT&p=true&ct=1698225794621&or=OWA%2DNT&cid=f7919d2f%2D3995%2D8a03%2Ddc38%2D8c5d1932920b&ga=1 

Ajoutez à votre analyse les éléments suivants :

Compléter la colonne ‘Attack’ avec la valeur ‘benign’ si elle n’est pas définie et la colonne ‘Label’ avec 0 si elle n’est pas définie
Identifiez et visualisez les outliers (d’après Isolation Forrest ; d’après LOF)
Visualisez par un LSTM et identifiez par une RMS-deviation les variations de l’ensemble des capteurs listés dans la documentation
Comparez 4 algorithmes de classification (Decision Tree, Random Forrest, XGBoost, MLP) pour identifier leur capacité de détection d’attaque sur le jeu de données. Visualisez le gain d’information associé à XGBoost pour la classification.
Bonus ; identifiez si certaines combinaisons de colonnes permettent d’identfier les attaques par détection d’outlier (non-supervisé) de manière satisfaisante par rapport à la classification (supervisée)
