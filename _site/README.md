LrxGaelle.github.io
===================
##Environnement de Dev : ##

- Apache // Configuration MySQL
  -->/terminal sudo /etc/init.d/apache2_status (verif si apache marche) mysql -u root -p ;
- Ruby
  --> ruby -v (quelle version installée) sudo apt-get install ruby1.9.3 ; sudo apt-get install ruby ruby-dev make ;
- Git
  --> sudo apt-get install git ;
- Jekyll
  --> sudo gem install jekyll –no-rdoc --no-ri ; 
  --> sudo apt-get install nodejs ;

##Installer son environnement :##

- Installer une machine virtuelle (ou cloner une existante)

##Sur machine Virtuelle :##

- Faire un répertoire « site » dans repertoire personnel sur xubuntu

##Sur Github :##

- Créer un compte github 
- Créer un "repositories" --> Username.github.io
- Configurer github https://pages.github.com

##Commande Git :##
- git add : ça va ajouter tout
- git commit -m : -m --> ajout d'un commentaire
- git push : envoie le dossier présent en local sur le site Github
- git remit -v : Tous les dépôts auquel est branché notre dépôt en local
- git push origin master : j'envoi vers origine (master=nom de votre dépôt principal)
- git pull origin master: on récupère les modifications
