# note 

## base

mkdir <creerUnRepertpore> --> créer un répertoire<br>
rm -R <NomDuRepertoire> --> Supprimer un répertoire<br>
touch <NomDuFichier> --> Créer un fichier<br>
rm <NomDuFichier> --> Supprimer un fichier<br>
mv <pathDuFichierOuDossier> <PathDestination><br>

## Gestion des utilisateurs
useradd -m <NomDuUser> -->Créer un utilisateur<br> 
sudo passwd <user> --> Changer le mot de passe de l'utilisateur<br>
userdel -R <user> Supprimer l'utilisateur et son répertoire<br>

## Gestion des groupes
sudo addgroup <NomDuGroupe> --> Créer un groupe<br>
sudo delgroup <SupprimerUnGroupe> --> Supprimer un groupe<br>
sudo adduser <NomUtilisateur> <NomGroupe> --> Ajouter un utilisateur à un groupe<br>
sudo deluser <nomUtilisateur> --group <NomDuGroupe> --> Supprime l'utilisateur du groupe<br>
sudo chown -R <NomUtilisateur> <NomGroupe> <DossierouFichier> --> changer les propriétaires et le groupe d'un dossier ou fichier<br>

## gestion des permissions

## Gestion des packages
sudo vim /etc/apt/sources.list 
