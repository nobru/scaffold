* NOBRU SCAFFOLD APPLICATION


** Start development server with basic informations

*** Create the project
```
composer create-project nobru/scaffold api
```

*** Start database
```
docker-compose -f vendor/nobru/framework/docker-compose.yml up -d
```

*** Configure application
```
bin/console nobru:framework:setup-application
```

*** Start server
```
symfony start:server
```

*** Access api application
[https://127.0.0.1:8000/](https://127.0.0.1:8000/)