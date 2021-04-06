travail à faire pour la prochaine séance:

1/ on dispose d'un fichier csv contenant des informations sur les étudiants.
on veut créer une simple application web qui affiche un tableau contenant l'ensemble des étudiants,
ligne par ligne (les colones sont: nom, prenom, ... voir le même ordre qu'en fichier csv). on appelle ça
un listing. donc réaliser le listing des données du fichier csv. c'est la première page du site (index.php)

2/ dans le listing une dernière colone est ajoutée pour mettre un lien hypertext qui renvoie vers la 
page profil.php
dans cette page, on affiche toutes les informations de l'étudiant crrespondant (à la façon d'un cv ... ou autre)

3/ revenir au listing (index.php), et penser à comment faire pour offrir une fonctionnalité de tri. on veut 
pouvoir trier le listing des élèves en fonction des colones (nom, ou prénom, ou moyenne, ...)
il n'est pas permis d'utiliser Javascript à notre stade. Mettre en place la fonctinnalité de trier le listing 
en implémentant le tri par fusion. 
indication (question 3): par colone, ajouter des boutons qui déclanche et recharge la page courante après avoir
réalisé le tri adéquatement. 

PS. chaque ligne du listing commence par une mignature de la photo d'identité de l'élève, et le profil de ce dernier 
doit absolumrnt contenir sa photo. si une photo n'existe pas on la remplace par défaut par un avatar par défaut "homme"
si c'est un garçon, sinon un avatar "femme".
