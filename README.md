# Formulaires_en_Sinatra

Welcome to Gossip Land
Sur la page d'accueil, vous aurez accès aux liens pour (1) ajouter un gossip, ou (2) lire l'un des gossips de la base de donnée.
Une fois sur la page du gossip sélectionner, vous pourrez (1) l'éditer, ou (2) revenir à la page d'accueil.

PS : la fonctionnalité d'edit ne fonctionne pas encore.


L'arborescence du programme est la suivante :
the_gossip_project_sinatra
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
        └── edit.erb
