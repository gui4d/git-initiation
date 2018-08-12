# git-initiation: 


rappel des commandes de base pour utiliser git et git hub:

----------------------------------------| utilitaire git  : depuis son terminal |---------------------------

git init : le dossier courant est maintenant versionné;

git add [my_files_or_directories...] : ajouter le fichier à l’index  (liste des fichiers destinées à être enregistrées tels quels) .

git status : voir l’enssemble des fichiers à l’index    

git commit  -m  ‘‘titre évocateur’’ : enregistrer la modification  dans l’historique 
git commit  -a  -m  ‘‘titre évocateur’’ : idem pour un/des fichier/s déjà indexé/s précédemment.
git commit --amend -m "titre vraiment évocateur" : cacher le dernier commit de l’historique et le remplacer par celui-ci (cacher des bourdes). 

git commit --hard : les fichiers retournent à la version du dernier commit.( attention !! à utiliser avec précaussion !! )  

git fetch : metre à jour son repository local sur le repository global. 

git rebase : mettre à jour la branche par rapport au master. 
git log : affiche l’historique des comits . 
------------------------------------------| interagir avec https://info.nohost.me/gogs/: toujour depuis son terminal |-----------------
erreur SSL certificate problem : entrer la ligne: git config --global http.sslVerify false

git clone [adresse du repository] : copie dans le dossier courant le repository sur le serveur .
git push [nom branche sur git hub ] : envoie les modifications  locales en ligne, dans la branche choisie sur git hub
git push -f [nom de branche sur git hub] : force l’envoie des modifications locales en ligne, utile en cas de divergence des branches (par exemple lors de commit amandées ).

------------------------------------------| interagir avec github.com : toujour depuis son terminal |-----------------------
 
git clone [adresse du repository] : copie dans le dossier courant le repository en ligne . 
git push [nom branche sur git hub ] : envoie les modifications  locales en ligne, dans la branche choisie sur git hub
git push -f [nom de branche sur git hub] : force l’envoie des modifications locales en ligne, utile en cas de divergence des branches (par exemple lors de commit amandées ).

