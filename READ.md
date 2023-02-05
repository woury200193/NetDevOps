Pour recupérer un dépot distant en local:
1- git clone url_du_depot_distant

pour pusher son depot à distance
NB: avant de faire ses command, il faut se déplacer dans repertoire de son depot en question
1- git remote add origin url_du_depot_distant
2- git push -u origin master
NB: pour les prochaine push vers le depot distant, on n'aura plus besoin de tou ça. Il faut juste saisir la commande:
git push (apres avoir faire le git add et git commit)

Pour push les tag
1-git push -m origin nom_du_tag

Pour appliquer les modif dans me depot local
1-git pull
