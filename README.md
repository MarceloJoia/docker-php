
# Setup Docker PHP 8.1
``

Suba os containers do projeto
```sh
docker-compose up -d
```


Acessar o container
```sh
docker-compose exec app bash
```


Instalar as dependências do projeto
```sh
composer install
```


Gerar a key para projeto Laravel
```sh
php artisan key:generate
```
