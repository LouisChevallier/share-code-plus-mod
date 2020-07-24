~~~~
NOTE
Projet installé tourne très bien. Fonctionnalités fonctionnent toutes.
Tentative de rajouter la langue avec un selecteur, mais mauvaise gestion des fichiers qui se multiplient.
Création des fichiers pour la bdd, pas parvenu à faire tourner la base de données et l'utiliser.
~~~~

# Share Code Plus

Extension de Share Code : meta données, log utilisateurs, SQL, coloration de code

## Téléchargez et installez le code de base

Placez vous dans un venv actif (onglet "Terminal" de PyCharm ou n'importe
quel terminal système où vous avez activé un venv déjà créé par ailleurs).
~~~~
(venv) $ git clone https://framagit.org/jpython/share-code-plus.git
(venv) $ cd share-code-plus
(venv) $ pip install -r requirements.txt
(venv) $ export FLASK_ENV=development
(venv) $ python sharecode.py
~~~~

Ouvrez un navitageur et allez à l'url : http://localhost:5000/


# Share Code Plus

 Voici Share Code Plus MOD, une plateforme qui permet de partager son code avec d'autres utilisateurs
 
 ## Créer, Editez, Partagez du code
 
 Utiliser les boutons pour réaliser vos actions sur le code à partager, un lien sera généré à chaque création afin de le partager directement avec vos collaborateurs !
