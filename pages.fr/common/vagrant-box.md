# vagrant box

> Gérer les boxes Vagrant (images de machines virtuelles).
> Voir aussi : `vagrant`.
> Plus d’informations : <https://developer.hashicorp.com/vagrant/docs/cli/box>.

- Lister toutes les boxes installées:

`vagrant box list`

- Ajouter une nouvelle box:

`vagrant box add {{hashicorp/bionic64}}`

- Ajouter une box à partir d'une URL personnalisée :

`vagrant box add {{ma-box}} {{https://example.com/ma-box.box}}`

- Supprimer une box installée:

`vagrant box remove {{hashicorp/bionic64}}`

- Mettre à jour toutes les boxes utilisées dans l'environnement Vagrant actuel:

`vagrant box update`

- Mettre à jour une box spécifique:

`vagrant box update --box {{bento/debian-12}}`

- Vérifier s'il existe une nouvelle version de la box utilisée :

`vagrant box outdated`

- Nettoyer les anciennes versions des boxes installées:

`vagrant box prune`
