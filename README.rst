Introduction à GIT
==================

Cours d'introduction à GIT
enseigné par `Pierre-Antoine Champin`_
au département informatique de l'`IUT de Lyon 1`_.

Il est publié à http://champin.net/enseignement/intro-git .

.. _Pierre-Antoine Champin: http://champin.net/
.. _IUT de Lyon 1: http://iut.univ-lyon1.fr/

Contribuer
++++++++++

Toute contribution à ce cours est la bienvenue.

Pour installer localement les sources et générer les fichiers HTML,
vous avez besoin de Sphinx_ et Hieroglyph_ .
Après avoir cloné ce dépôt,
vous devez exécuter une fois les commandes suivantes
afin de récupérer le thème utilisé ::

  git submodule init
  git submodule update

puis, pour générer les documents ::

  make publishable

.. _Sphinx: http://sphinx-doc.org/
.. _Hieroglyph: http://hieroglyph.io/
