# Projet_machine_learning
Projet de maching learning ayant pour but de prédire des véhicules de la marque Hyundai sur un data set de prix de voitures. Le but de ce projet est de créer un modèle de prédiction performant permettant de prédire le prix des voitures Hyundai.

Voici les différentes étapes afin de lancer le script :

légende : 
"-->" : signifie "étape"
" - " : signifie "commande à entrer sur la cli"

méthode d'utilisation :

--> Téléchargez le git et mettez le dans un répertoire facile d'accès. 
Ou alors, depuis CLI : 
- git clone https://github.com/Zapphyrr/Projet_machine_learning.git

--> en CLI : accédez à votre dossier cloné via un 
- cd Projet_machine_learning

--> créer un environnement virtuel :
(si python n'est pas installé : - sudo apt install python3 python3-pip -y)
- python3 -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
    
--> Executer le notebook :
(si probleme d'installation de package veuillez à suivre les 5 prochains lignes)
- sudo apt install jupyter-core
- pip install nbconvert
- pip install --upgrade jupyter nbconvert
- pip install pandas seaborn matplotlib
- pip install scikit-learn

Executer ensuite cette commande :
- jupyter nbconvert --to notebook --execute projet_desvoy_maching_learning.ipynb --output result.ipynb

--> Exécuter le Script Python :
- jupyter nbconvert --to script projet_desvoy_maching_learning.ipynb
- python projet_desvoy_maching_learning.txt
