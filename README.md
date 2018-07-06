# git-initiation: 


rappel des commandes de base pour utiliser git et git hub:

----------------------------------------| utilitaire git  : depuis son terminal |---------------------------
-------création d'un nouveau repository/

git init : le dossier courant est maintenant versionné;
git add [my_files_or_directories...] : ajouter le fichier à l’index  (liste des fichiers destinées à être enregistrées tels quels) .

git status : voir l’enssemble des fichiers à l’index    

git commit  -m  ‘‘titre évocateur’’ : enregistrer la modification  dans l’historique 
git commit  -a  -m  ‘‘titre évocateur’’ : idem pour un/des fichier/s déjà indexé/s précédemment.
git commit --amend -m "titre vraiment évocateur" : cacher le dernier commit de l’historique et le remplacer par celui-ci (cacher des bourdes). 
git commit reset –hard : les fichiers retournent à la version du dernier commit. 
git log : affiche l’historique des comits . 


---------modification d'une branche/ 

si ce n'est pas déjà fait: 

/dans le terminal , placer vous dans le dossier de travail 
/si ce n'est pas déjà fait : taper 
    git config --global user.email "you@example.com"
    git config --global user.name "Your Name"

/taper :
    git clone [nom du repository.git]
    git chekout -b [nom-de-branche-evocateur]
    git branch  #verifier que la branche est bien présente 
    Code [nom du fichier a modifier/creer] 
/faire les modifications/ajouts sur les fichiers que l'on veut 
    git add [nomDesFichiersChangées1] [nomDesFichersChangées2]
    git status # verifier l'index 
    git commit -m "un titre explicant les objectifs du commits"
    git branch #verifier que les branches sont à jour 
    git push --set-upstream origin [nom-de-la-branche-evocateur] #envoyer en ligne la branche 