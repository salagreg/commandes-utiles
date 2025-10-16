## Installer la bibliothèque de requêtes :

- *Vérifier l'installation* : python3 -m pip show requests
- *Installer la bibliothèque* : python3 -m pip install requests

## Développer une API simple à l'aide de Python avec Flask :
- *Créer un environnement* : mkdir myproject
                           cd myproject
                           python3 -m venv .venv
- *Activer l'environnement* : . .venv/bin/activate
- *Installer Framework Flask* : pip install Flask
- *Installer Flask-HTTPAuth* : pip install Flask-HTTPAuth
- *Installer Flask-JWT-Extended* : pip install Flask-JWT-Extended

## Créer une clé secrète :
*commande terminal* : python3 -c "import secrets; print(secrets.token_urlsafe(32))"

## Installer Swagger :
*commande terminal* : python3 -m pip install flasgger
