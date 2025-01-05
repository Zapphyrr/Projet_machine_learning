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
- python -m venv venv
- source venv/bin/activate
- pip install -r requirements.txt
    
--> Executer le notebook :
- jupyter nbconvert --to notebook --execute projet_desvoy_maching_learning.ipynb --output result.ipynb

--> Exécuter le Script Python :
- jupyter nbconvert --to script projet_desvoy_maching_learning.ipynb
- python projet_desvoy_maching_learning.py
