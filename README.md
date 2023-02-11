# test-tempo-docker-compose

## Documentacion
La documentación para ejecución 
```
- Debe tener instalado docker y corriendo
- Verificar que en máquina local no esté corriendo nada en puertos 5432,6379 8080 y 8081
- Verificar que en docker no esté corriendo nada en puertos 5432,6379 8080 y 8081
```



Para levantar todo el stack 
```sh
$ docker-compose up
```
## Documentacion del API
La documentación en formato OpenAPI está disponible [aquí](http://localhost:8080/tempo/swagger-ui/index.html) <br />
La colección de postman está disponible [aquí](https://raw.githubusercontent.com/oscarygutierrezg/test-tempo-docker-compose/main/Tempo.postman_collection.json)