Bienvenue sur le repository Rails de Evan Bourgouin

Ce projet crée une base de donnée pour le projet Gossip.

Les utilisateurs peuvent créer des potins : "askip john est célib hihi"
Les utilisateurs en créant des potins peuvent mettre un ou plusieurs tags sur les potins : #romance
Les utilisateurs peuvent commenter des potins : "ahiii j'savé pa lol 💁‍♂️"
Et puisqu'une appli de potins sans un système BG de commentaire serait bidon, on va faire en sorte qu'il est possible de commenter des commentaires
Les utilisateurs peuvent liker des potins
Les utilisateurs peuvent contacter leur commères favories en MP pour des exclus mondiales
L'utilisateur pourra donc rechercher les potins par ville, par utilisateurs, par date (plus récent ou plus ancien), par nombre de likes, par tags, pour trouver les potins les plus croustillants.

Pour tester l'appli, réalisez les processus suivants :

pour copier le repo sur votre machine

git clone https://github.com/Cyran0/Gossip_Project

pour se déplacer dans le bon dossier

cd GossipProject/

pour mettre à jour la liste de gems

bundle install

pour que les migrations soient bien effectuées

rails db:migrate

pour pouvoir initialiser et remplir la database

rails db:seed

La base de données complète se trouve (normalement) au chemin d'accès suivant :

GossipProject/db/development.sqlite3

Ouvrez-la avec DB Browser ou SQLStudio
