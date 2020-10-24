# Três Cinco Pimba (FizzBuzz)

### Estrutura:
```
app
├── composer.json
├── docker-compose.yml
├── Dockerfile
├── phpunit.xml
├── src
│   ├── CountPimba.php
│   └── main.php
└── tests
    └── CountPimbaTest.php
```
----

### Rodando e acessando o container Docker:

`docker-compose up -d`

`docker exec -it trescincopimba bash`


#### Scripts
<small>(Dentro do container do docker)</small><br>
<b> Testes Unitários </b>

Dentro da pasta app/

`composer run test`


<b> Script main.php </b>

Dentro da pasta app/src/

`php main.php`

-----

### Usando o PHP e Composer local
<b> Testes Unitários </b>

Dentro da pasta app/

`composer run test`

<b> Script main.php </b>

Dentro da pasta app/src/

`php main.php`

-----------
Author: [@LutzGe](https://github.com/LutzGe)