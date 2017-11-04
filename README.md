<b>LILASENA</b> (https://fayechartre6.000webhostapp.com/exos/lilasena/)<br>
<b>Header Site v2</b> (https://fayechartre6.000webhostapp.com/exos/exo7-menusitev2.html)<br>
<b>LINGERIE</b> (https://fayechartre6.000webhostapp.com/exos/lingerie/)<br>
<b>SONOMAD</b> (https://fayechartre6.000webhostapp.com/exos/sonomad/)<br>
<b>PUBLICATION FACEBOOK</b> (https://fayechartre6.000webhostapp.com/exos/exo-test02-50mn.html)<br>
<b>ALLOCINE</b> (https://fayechartre6.000webhostapp.com/exos/exo-test01-50mn.html)<br>
<b>Balises</b> (https://fayechartre6.000webhostapp.com/exos/balise-01.html)<br>
<b>Login</b> (https://fayechartre6.000webhostapp.com/exos/exo4b.html)<br>
<b>Navigation</b> (https://fayechartre6.000webhostapp.com/exos/exo5-nav.html)<br>
<b>Article</b> (https://fayechartre6.000webhostapp.com/exos/Article.html)<br>
<b>Article Vertical</b> (https://fayechartre6.000webhostapp.com/exos/exo6-articleb.html)<br>
<b>Header site</b> (https://fayechartre6.000webhostapp.com/exos/exo7-menusite.html)<br>
<b>Position</b> (https://fayechartre6.000webhostapp.com/exos/exo9-position.html)<br>
<b>Page LI</b> (https://fayechartre6.000webhostapp.com/exos/exo10-li.html)<br>
<b>Position BG</b> (https://fayechartre6.000webhostapp.com/exos/exo11-bg.html)<br>


# Etape à suivre pour gérer des fichiers/dossiers
Pour connaitre les Commandes GITHUB se référer à ce repo : https://github.com/icmrprojet/isaProject-test 

#### PREMIERE ETAPE - CREATION CLONAGE
1. Créer le projet sur GITHUB avec un fichier README.md
2. Faire un clone du Projet et le positionner dans le repertoire LOCAL choisi en y ajoutant un fichier <b style="color:red">`.gitignore`</b>

#### DEUXIEME ETAPE - ENVOIE DES DONNEES LOCALES
1. Placer tous les fichiers à traiter dans ce répertoire LOCAL
2. Se placer dans ce repertoire via la console avec la commande cd +rep
3. Faire le premier <b style="color:blue">`git add .`</b> pour tout selectionner
4. Faire le premier <b>`git commit -m "initial commit" `</b> pour préparer le commit sur GITHUB
5. Faire le premier <b>`git push origin master`</b> pour "effectuer" le commit initial du master

#### TROISIEME ETAPE - VERIFICATION WEB
1. Sur GITHUB vérifier que tous les fichiers ont bien été downloadé dans le master du projet

#### QUATRIEME ETAPE - CREATION DE BRANCH
1. Revenir dans la console et créer une branche : <b>`git branch nom_branch`</b>
2. Se positionner dans cette nouvelle branche : <b>`git checkout nom_branch`</b>, le nom de la branch apparait en cyan à la fin des lignes
3. Supprimer une branche : <b>`git -D nom_branch`</b>. La suppression sera visible sur GITHUB seulement après le prochain PUSH.

#### CINQUIEME ETAPE - MISES A JOUR
1. Toujours revenir dans ce répertoire LOCAL pour faire les modifications.
2. Refaire un <b style="color:blue">`git add .`</b> ou <b style="color:blue">`git add .`</b> avec le nom du fichier
3. Refaire un <b>`git commit -m "message de mise à jour" `</b> pour expliquer le contenu du commit sur GITHUB
4. Refaire un <b>`git push origin nom_branch`</b> pour "effectuer" le commit sur la branche et non sur le master

#### ERROR ETAPE 
1. En cas d'erreur "behind 12 commit"
2. Faire sur le master <b style="color:blue">`git stash`</b> pour remiser le code : https://git-scm.com/book/fr/v1/Utilitaires-Git-Le-remisage
3. Puis faire un <b>`git pull origin master`</b>
4. Suivi d'un <b>`git push origin master`</b>

#### REVENIR A UNE VERSION ANTERIEURE 
1. Faire sur le master <b style="color:blue">`git log`</b> pour visualiser toutes les détails des commits QUI, QUAND, QUOI.
* **Methode 1**
  * Faire <b style="color:blue">`git reset --hard 4494146`</b> pour reset ce commit
  * Suivi de <b style="color:blue">`git reset --hard 4494146`</b> pour reset ce commit
* **Methode 2**
  * Faire <b style="color:blue">`git revert --hard 4494146`</b> pour revert ce commit
  * Suivi d'un <b>`git push origin master`</b>

#### Pour sortir de l'EDITEUR
<b>:q!</b>  ou CTRL C


