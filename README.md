# Blog de Ishaq ZOUAGHI

Vous trouverez sur ce blog :

* des *billets* : un format court utilisés pour poser sur écrit mes découvertes sur les différentes technologies du moment ;
* des *articles* : réflexion plus longue sur un sujet particulier ;
* des *ateliers* : ensemble d'exercices hébergés sur [Github].

Vous ne trouverez pas sur ce blog (et mes médias sociaux) :

* des choses en relation avec la politique ;
* des informations sur ma vie privée ;
* des photos qui ne servent pas les technologies que je surveille (des chats mignons par exemple).

## Construire avec Jekyll

```console
$ bundle exec jekyll serve
```

## Construire avec Docker

```console
$ docker run --rm --volume="$PWD/mickaelbaron.github.io:/srv/jekyll" --volume="$PWD/bundles:/usr/local/bundle" -p 4000:4000 -it jekyll/jekyll:latest jekyll serve
```

> Le dépôt contient de nombreux petits fichiers, l'utilisation de Docker sous macOS peut amener à de gros ralentissement.

## Crédits

Ce blog a été construit à partir de Jekyll et il utilise l'excellent thème [portfolYOU] proposé par [Youssef Raafat].

Le système de commentaire basé sur Twitter a été inspiré par ce [billet](https://flamiszoltan.me/twitter-as-comment-system).

Le générateur de tables des matières utilise le projet [jekyll-toc](https://github.com/allejo/jekyll-toc).

[portfolYOU]: https://github.com/YoussefRaafatNasry/portfolYOU
[Github]: https://github.com/IshaqZOUAGHI