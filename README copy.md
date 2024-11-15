# documentation

Ce dépôt centralise tous les documents liés à l'analyse, la conception, et le rapport final de Soli-LMS.

## Cloner le dépôt

````bash
git clone https://github.com/soli-lms/soli-lms_documentation.git
#Initialiser et mettre à jour les sous-modules
git submodule init
git submodule update
````

## Insertion des modules au dépôt

````bashcreate
git submodule add https://github.com/soli-lms/pkg_rh_docs.git pkg_rh
git submodule add https://github.com/soli-lms/pkg_competences_docs.git pkg_competences
git submodule add https://github.com/soli-lms/pkg_creation_projets_docs.git pkg_creation_projets 
git submodule add https://github.com/soli-lms/pkg_creation_tache_docs.git pkg_creation_tache
````


## Exécution de rapport localement sans github pages



````bash
# Installation
bundle install

# Exécution
serve.ps1
````


## Rapport et Présentation 

- [Rapport](https://soli-lms.github.io/soli-lms_docs/)
- [Présentation](https://soli-lms.github.io/soli-lms_docs/)