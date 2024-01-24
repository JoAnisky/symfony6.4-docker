# Symfony6.4-docker

Une fois ce repo cloné :

- Creer un dossier à la racine pour y stocker l'application (par ex : app)
  
- Créer un dossier "mysql" qui permettra d'avoir une persistance de la base de données

## Build l'image et lancer le conteneur

Se placer à la racine du projet cloné et lancer la commande

```shell
docker-compose up --build
```

Aller à l'interieur du conteneur pour pouvoir lancer des commandes

```shell
docker-compose exec php bash
```

Toutes les commandes Symfony se lancent DANS le conteneur
