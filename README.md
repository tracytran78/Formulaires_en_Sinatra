#Formulaires_en_Sinatra

## Installation et utilisation
1. Placez vous où vous souhaitez cloner le Gossip en ligne
2. ```$ git clone https://github.com/tracytran78/Formulaires_en_Sinatra ```
3. ```$ cd THP_sinatra```
4. ```$ bundle install```
5. ```$ shotgun -p 4567```
6. Allez sur la page http://localhost:4567/


## Contenu
Welcome to Gossip Land
Sur la page d'accueil, vous aurez accès aux liens pour (1) ajouter un gossip, ou (2) lire l'un des gossips de la base de donnée.
Une fois sur la page du gossip sélectionner, vous pourrez (1) l'éditer, ou (2) revenir à la page d'accueil.

PS : la fonctionnalité d'edit ne fonctionne pas encore.


## L'arborescence du programme est la suivante :
THP_sinatra
```
├── READLE.md
├── Gemfile
├── Gemfile.lock
├── config.ru
├── db
│   └── gossip.csv
└── lib
    ├── controller.rb
    ├── gossip.rb
    └── views
        ├── index.erb
        └── new_gossip.erb
        └── show.erb
        └── edit.erb ```
      
        
       
### config.ru
Fichier de configuration Rack, lancé avec Shotgun, cela permet de faire tourner le serveur et de tester des changements en rafraichissant la page
### lib
#### controller.rb
Gère les routes et les méthodes GET / POST
#### gossip.rb
C'est le fichier qui contient la classe Gossip 
#### db/gossip.csv
C'est la database au format csv
#### views
Ce dossier contient les differentes views

