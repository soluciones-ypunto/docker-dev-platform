Basic setup
===============

- Crear una red nombrada nginx-proxy
```sh
    docker network create nginx-proxy
```
- Crear un volumen nombrado portainer_data
```sh
    docker volume create portainer_data
``` 
- Editar los valores de .env según conveniencia
- Ejecutar 
```sh
    docker-compose up -d
```

