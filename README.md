# R101_1

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/iutVilletaneuseDptInfo/R101_1/master)

Bases de la programmation

Ce dépôt contient les ressources pour le cours R101_1 du département de l'IUT de Villetaneuse. Ces ressources sont libres mais sous copy left.

## Accès aux données du dépôt 
*Pour copier les données* dans un répertoire, utiliser la commande 
```
git clone git@github.com:iutVilletaneuseDptInfo/R101_1.git
```
Cela crée un dépot git intitulé R101_1.

*Pour mettre à jour les données*, ouvrir un terminal dans le répertoire R101 et utiliser les commandes
```
git commit -am 'MaJ'
git pull
```

## Environnement interactif : Jupyter Notebook et Python Tutor

### Jupyter Notebook 
On utilise **Jupyter Notebook**  http://jupyter.org/ pour les supports de cours-TD-TP
Jupyter Notebook est installable notamment avec Anaconda https://www.anaconda.com/download/

Commande de lancement : `jupyter-notebook`

### Python Tutor 
 **Python Tutor**  permet permet de visualiser l'exécution d'un code en python, ce qui aide à comprendre son fonctionnement.
 
*Pour l'installer*, il faut utiliser les commandes suivantes 
```
    git clone https://github.com/kandjiabdou/visual_pytutor.git
    
    jupyter nbextension install visual_pytutor
    
    jupyter nbextension enable visual_pytutor/main
```    
Sur les machines de l'IUT seule la dernière commande est nécessaire. Elle doit être exécutée avant le lancement du notebook.

*Pour visualiser le code* : cliquer sur l'oeil qui apparait à gauche de chaque cellule de code, une fenêtre de suivi d'exécution s'ouvre alors. 

## Environnement de travail à l'IUT
Pour aller dans votre répertoire personnel et y conserver vos programmes, la commande
```
cd Mes_Montages/numero_etudiant 
```
permet d'accéder à votre repertoire personnel

Ouvrir avec le clic droit de la souris un terminal dans `Mes_Montages` et lancer Python Tutor et Jupyter notebook. 

## Mise à jour automatique du dépôt

Pour mettre à jour automatiquement le dépôt (ie, récupérer les nouveaux chapitres), vous pouvez exécuter le script `updateDepot` situé dans le répertoire cloné :
```bash
./updateDepot
```


## Contributeurs pour la réalisation de ces supports de cours :
* Hanane Azzag
* Frédérique Bassino
* Thierry Charnois
* Evaggelos Kritsikis
* Mathieu Lacroix
* Mustapha Lebbah
* Bouchaïb Lemaire
* Guillaume Santini
