# mutantes-registry
NetFlix Eureka Server responsable por permitir la comunicación entre los servicios sin tener que saber el hostname o el puerto. 

## Dependencias
Servicios que se registrarán en `mutantes-registry`:

1. [mutantes-api](https://github.com/arthurmessias/mutantes-api) - Analizador de una cadena de ADN
2. [mutantes-db-api](https://github.com/arthurmessias/mutantes-db-api) - Capa de persistencia
3. [mutantes-gateway](https://github.com/arthurmessias/mutantes-gateway) - API-Gateway


## Para clonar este repositorio
```bash
git clone https://github.com/arthurmessias/mutantes-registry.git
cd mutantes-registry
```

## Unit tests
No aplica

## Start Service Registry
```bash
mvn spring-boot:run
```

## Endpoints
Eureka home

* Local endpoint: http://localhost:8761
* Heroku endpoint: https://mutantes-registry.herokuapp.com
