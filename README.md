FiatCar | Sistema de Gerenciamento de mecânica de veículos

- Tecnologias:
```sh
Php 8.0.3
Laravel Framework 8.65
MySQL 5.7.22
Docker 20.10.10
nginx
```

- Instalação

Criar uma cópia do arquivo .env.example e renomear para .env

Suba os containers do projeto
```sh
docker-compose up -d
```

Acessar o container
```sh
docker-compose exec teste_appmax bash
```

Instalar as dependências do projeto
```sh
composer install
```

Gerar a key do projeto Laravel
```sh
php artisan key:generate
```

Gerar as Tabelas e dados do banco:
```sh
php artisan migrate
php artisan db:seed
```

Rodar os testes dos endpoints
```sh
./vendor/bin/phpunit
```

- Desenvolvedor oficial
```sh
Pablo Fabrício - fabriciopablo2000@gmail.com
```
