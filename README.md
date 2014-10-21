rozenn
======
Procédure

Créer une machine virtuelle

sudo apt-get install 	apache
				mysql-sever
				ruby
				jekyll
				git

Créer un compte Github
Créer un répertoire Github
Prend l'url du clone répertoire
htttps://github….

Créer le répertoire "site" dans le dossier personnel de la machine virtuelle et sur github

On génére une ssh keys:
setting> SSH keys>generating > download Github for mac > Intall > saisir données compte github une ssh key est génére à l'email du compte github

Terminal
xubuntu/site (création d'un dossier site), ouvrir un terminal ici 
git clone https///github.com/laot.github.io.git
 
La clé ssh est dans le fichier "site"

sur le compte github aller dans "setting/ssh keys et cliquer sur "genette ssh keys"

Choisir le nom et entrer la clé ssh reçue dans le répertoire site

Sur la machine virtuelle aller dans etc/apache2/apache2.cont et faire un ledit pour rajouter les droits sur le dossier  /home/xubuntu/site

Aller dans sites-available et modifier le fichier 00-defaut.cont avec ledit pour DocumentRoot et mettre /home/xubuntu/site/site
				
