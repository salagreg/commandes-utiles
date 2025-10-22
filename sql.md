## Installer MySQL via Homebrew : 

*Une fois Homebrew installé:* 
- brew install mysql
- brew tap homebrew/services

*Démarrer MySQL :*   brew services start mysql
*Si le service est déjà lancé, tapez la commande :*    brew services restart mysql
*Vérifier qu’il tourne avec :*    brew services list et/ou mysql -V

## Tester MySQL : 

mysql -u root


## Créez le mot de passe de l’utilisateur root de notre BDD :

- mysqladmin -u root password '<motdepasse>'
- mysql -u root  -p
