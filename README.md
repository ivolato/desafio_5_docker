# Docker + docker-compose
Este trabajo tiene como objetivo desarrollar un build en docker y configurar un entorno
local para que corra una aplicación de NestJS con docker-compose.


## Clonar el repositorio.
```
git clone https://github.com/ivolato/desafio_5_docker.git
```

## Iniciamos los contenedores.
```
cd desafio_5_docker
docker-compose up -d --build
```
En este paso construimos la imagen que se utilizara en el contenedor para la app NestJS.
Además creamos el contenedor para MongoDB y la red que conecta los contenedores.


