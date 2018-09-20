# Site Internet du Club Robot

Ce nouveau site a pour but de remplacer l'[ancien site](https://etud.insa-toulouse.fr/~club_robot/), totalement dépassé et pas mis à jour.

Il a plusieurs objectifs :
* le rendre bien plus maintenable
* avoir une interface plus avenante
* entreposer le site sur github pour un contrôle centralisé des ressources numériques du club
* écrire des articles facilement avec un joli affichage en Markdown

Pour ce faire, le site utilise un [thème jekyll](https://jekyllrb.com/), [Notepad](https://github.com/hmfaysal/Notepad). L'hébergement d'un site sur [<name>.github.io](https://clubrobotinsat.github.io/) l'oblige à être statique.

Pour pouvoir visualiser en local le site, il faut installer `bundler` (un truc en Ruby) ; il faut d'abord avoir python-pip installé.

Ensuite, ces commandes devraient tout installer :

```bash
sudo pip install cheat
sudo gem install rdoc bundler jekyll

curl -O http://mirror.veriportal.com/gnu/gsl/gsl-2.5.tar.gz
tar xvzf gsl-2.5.tar.gz
cd gsl-2.5
./configure
make
sudo make install
sudo gem install --conservative --no-ri --no-rdoc gsl

bundler update
```
