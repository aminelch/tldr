# vagrant

> Gère des environnements de développement légers, reproductibles et portables.
> Plus d’informations : <https://www.vagrantup.com>.

- Crée un fichier Vagrantfile dans le répertoire actuel avec la box Vagrant de base :

`vagrant init`

- Crée un fichier Vagrantfile avec la box Ubuntu 20.04 (Focal Fossa) depuis HashiCorp Atlas :

`vagrant init ubuntu/focal64`

- Démarre et provisionne l’environnement Vagrant :

`vagrant up`

- Suspend la machine :

`vagrant suspend`

- Arrête la machine :

`vagrant halt`

- Se connecte à la machine via SSH :

`vagrant ssh`

- Affiche la configuration SSH de la machine Vagrant en cours d’exécution :

`vagrant ssh-config`

- Liste toutes les boxes locales :

`vagrant box list`
