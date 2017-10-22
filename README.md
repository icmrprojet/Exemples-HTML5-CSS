Login (https://fayechartre6.000webhostapp.com/exos/exo4b.html)
Navigation (https://fayechartre6.000webhostapp.com/exos/exo5-nav.html)
Article (https://fayechartre6.000webhostapp.com/exos/Article.html)
Article Vertical (https://fayechartre6.000webhostapp.com/exos/exo6-articleb.html)
Header site (https://fayechartre6.000webhostapp.com/exos/exo7-site.html)
Position (https://fayechartre6.000webhostapp.com/exos/exo9-position.html)
Page LI (https://fayechartre6.000webhostapp.com/exos/exo10-li.html)
Position BG (https://fayechartre6.000webhostapp.com/exos/exo11-bg.html)

# Etape à suivre pour gérer des fichiers/dossiers
Pour connaitre les Commandes GITHUB se référer à ce repo : https://github.com/icmrprojet/isaProject-test 

#### PREMIERE ETAPE - CREATION CLONAGE
1. Créer le projet sur GITHUB avec un fichier README.md
2. Faire un clone du Projet et le positionner dans le repertoire LOCAL choisi en y ajoutant un fichier <b style="color:red">.gitignore</b>

#### DEUXIEME ETAPE - ENVOIE DES DONNEES LOCALES
3. Placer tous les fichiers à traiter dans ce répertoire LOCAL
4. Se placer dans ce repertoire via la console avec la commande cd +rep
5. Faire le premier <b style="color:blue">git add .</b> pour tout selectionner
6. Faire le premier <b>git commit -m "initial commit"</b> pour préparer le commit sur GITHUB
7. Faire le premier <b>git push origin master</b> pour "effectuer" le commit initial du master

#### TROISIEME ETAPE - VERIFICATION WEB
8. Sur GITHUB vérifier que tous les fichiers ont bien été downloadé dans le master du projet

#### QUATRIEME ETAPE - CREATION DE BRANCH
9. Revenir dans la console et créer une branche : <b>git branch nom_branch</b>
10. Se positionner dans cette nouvelle branche : <b>git checkout nom_branch</b>, le nom de la branch apparait en cyan à la fin des lignes

#### CINQUIEME ETAPE - MISES A JOURS
11. Toujours revenir dans ce répertoire LOCAL pour faire les modifications.
12. Refaire un <b style="color:blue">git add .</b> ou <b style="color:blue">git add .</b> avec le nom du fichier
13. Refaire un <b>git commit -m "message de mise à jour"</b> pour expliquer le contenu du commit sur GITHUB
14. Refaire un <b>git push origin nom_branch</b> pour "effectuer" le commit sur la branche et non sur le master
