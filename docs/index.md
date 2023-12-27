# Laravel

Pour consulter la documentation complète, veuillez visiter [laravel.com](https://laravel.com/docs/10.x).

## Commandes

* `composer create-project laravel/laravel example-app` - Créez un nouveau projet Laravel.
* `cd example-app`
* `php artisan serve` - Lancez le serveur de développement local de Laravel.

## Laravel Sail

* Laravel Sail est un outil en ligne de commandes permettant d'interagir avec un environnement de développement sous docker.

* `curl -s https://laravel.build/mon-application | bash` 
* Une fois cette commande terminée, une nouvelle installation de Laravel disponible et située dans un dossier mon-application.
* Les services installés par défaut sont MySQL, Redis, Meilisearch, Mailpit et Selenium.
* Pour spécifier les services et le nom de l'application : `curl -s "https://laravel.build/app?with=mysql,mailpit" | bash` 

### Lancer Laravel avec Sail
* `./vendor/bin/sail up`
* `./vendor/bin/sail stop`

### Structure et configuration de Laravel

```
Laravel   
│
└───app
│   
└───bootstrap
│ 
└───config
│ 
└───database
│ 
└───public
│ 
└───ressources
│ 
└───routes
│ 
└───storage
│ 
└───tests
│ 
└───vendor
```
