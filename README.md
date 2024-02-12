# SUJET_4ETI_AdmCO_20232024 Julie

**Activités AdmCo Partie 1 2023-2024**


## Questions Préparatoires

  1. Expliquer le code suivant  (addition.py):
```python
def add(x, y):

  z=x+y

  print('add() executed under the scope: ', __name__)

  return z

if __name__ == '__main__':

  x=input('Enter the first number to add: ')

  y=input('Enter the second number to add: ')

  result = add(int(x),int(y))

  print(x, '+', y,'=', result)

  print('Code executed under the scope: ', __name__)
```

Ce code définit une fonction add(x, y) qui prend deux paramètres x et y, les additionne pour obtenir z et affiche un message indiquant que la fonction add() est exécutée, puis retourne z. Ensuite, il vérifie si le nom du module est '__main__', si c'est le cas, il demande à l'utilisateur d'entrer deux nombres, appelle la fonction add() avec ces nombres convertis en entiers, puis affiche le résultat de l'addition et un message indiquant que le code est exécuté sous la portée __name__.

Pour chaque question, indiquez vos sites choisis pour reference ( où le prompt de l'outil d'IA utilisé)

  1. A quoi sert requirments.txt ?

     Un fichier requirements.txt est utile pour que sur un même projet tout le monde est le même environnement virtuel.

  1. A quoi ressemble un module en python ?

     Un module en python est un fichier contenant du code Python. Le code peut être constitué de fonctions, de classes et de variables.      On peut aussi importer un module dans un autre fichier Python.

  1. A quoi ressemble un package ?

     Un package en python est un ensemble de modules regroupés dans un dossier. Il contient un fichier appelé ‘__init__.py’ qui indique      à Python que le répertoire doit être considéré comme un package.

  1. Créer un code python utilisant sous forme de module addition.py

     import * from addition
     print (“le résultat est :”, add(1,2))


  1. A quoi sert pip ?

     Pip est un gestionnaire de paquets pour python, il permet d’installer et de gérer des packages.

  1. A quoi sert PYTHONPATH ?

     PYTHONPATH est une variable d’environnement qui indique dans quel répertoire il est nécessaire de chercher le module ou package         demandé.

  1. Où sont stockés les paquets installé par pip ?

     Les paquets installés par pip sont stockés dans le répertoire : site-packages. Ce répertoire n’a pas toujours le même emplacement       mais pour savoir où il est on peut utiliser la commande : pip show.

  1. A quoi sert pip install –user ?

     La commande pip install -user sert à installer des packages seulement pour cet utilisateur et non pas pour l’ensemble du système.

  1. A quoi sert venv ?

     Venv sert à créer et gérer des environnements virtuels pour Python.

  1. Comment utiliser venv ?

     On utilise venv afin de créer un environnement en écrivant : python -m venv <environment name>

  1. A quoi sert docker ?

     La plateforme logicielle docker sert à simplifier le développement, le déploiement et la gestion des applications en utilisant des      conteneurs légers et portables qui permettent la création d'environnements isolés.

  1. Comment utiliser docker ?

     Il faut l’installer sur notre système d’exploitation puis pour le lancer il faut écrire la commande : docker run -it ubuntu.

## Exercice 0

1. A quoi sert git config , Quelles sont les informtions minimales à renseigner. Est ce bien fait sur votre ordinateur ?

'git config' permet de configurer les paramètres de Git. Les informations minimales à renseigner sont le nom d'utilisateur et l'adresse e-mail associée aux commits.

1. Quelles sont les commandes de bases git ? a quoi servent elles ?
   
Les commandes de base de Git incluent git init pour initialiser un nouveau dépôt, git add pour ajouter des fichiers à l'index, git commit pour enregistrer les modifications dans l'historique, git push pour pousser les modifications vers un dépôt distant, et git pull pour récupérer les modifications depuis un dépôt distant. Ces commandes sont essentielles pour la gestion des versions et la collaboration dans un projet Git.

Expliquez a quoi correspond ce worklow et pourquoi c'est une bonne pratique 
![ Workflow git ](images/git-model@2x_m.png)


 Pour cette exercice j'ai fait un dépot github : <https://github.com/julieldg/TEST_worflowgit_Ludwig>

 En haut du README.md il y a plusieurs "Modif ..." qui correspondent a chaque commit que j ai effectué pour obtenir l'arborescence que j'ai mis en photo dans le lien.

 # Exercice 

 L'ensemble des exercices se trouvent ici : <https://gitlab.com/administration-syst-me-et-gestion-de-code-partie-1>

 Il y a bien un projet gitlab pour chaque exercice.

 Pour chaque exercice, l'objectif de ce dernier est expliqué. De plus il y a la réalisation qui est détaillée ainsi que le lancement du programme, si il y a quelques chose d'inhabituelle. J'y ai rajouté aussi l'arborescence du projet, dès qu'il est devenu un peu complexe.

Dès qu'il faut installer des packages, la bonne pratique est de se mettre dans un environnement virtuel avec la commande :
"python3 -m venv test"
puis :
"source ./venv/bin/activate "


**Ressources utilisées** 

<https://gitlab.com/fabricejumel/rendufinal_bouyssoux/>

<https://gitlab.com/fabricejumel/tp1_ex8v0>

ChatGPT

<https://python-packaging-tutorial.readthedocs.io/en/latest/uploading_pypi.html>

[<https://python.doctor/page-virtualenv-python-environnement-virtuel>](https://docs.python.org/fr/3/library/venv.html)

<https://docs.python.org/fr/3/howto/logging.html>

<https://realpython.com/python-modules-packages/>

<https://packaging.python.org/tutorials/installing-packages/>

<https://python.doctor/page-black-code-formatter>

<https://realpython.com/python-code-quality/>

<https://docs.python.org/fr/3.9/library/unittest.html>

<https://courspython.com/modules.html>






